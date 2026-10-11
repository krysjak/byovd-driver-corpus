# BYOVD — how signed vulnerable drivers get used, and how to detect it

## The model

Bring Your Own Vulnerable Driver: a legitimate, properly signed kernel
driver that exposes controllable IOCTL primitives. Because it is signed, it
loads on machines where unsigned code is rejected (HVCI off; on some builds
even with HVCI if the cert predates blocklisting). Once loaded, a user-mode
process talks to it through its device object and gains kernel-mode
capabilities it should never have had.

## Generic loading pattern

The publicly documented pattern (identical to what LOLDrivers publishes in
its `Commands` field, and what EDR telemetry looks for):

```
sc.exe create <name> binPath=C:\path\to\driver.sys type=kernel
sc.exe start <name>
```

Equivalent paths: `NtLoadDriver`, `ZwLoadDriver`, writing
`HKLM\SYSTEM\CurrentControlSet\Services\<name>` directly, or abusing an
already-installed legitimate service whose driver is on disk.

After the service starts, user-mode code does:

```
h = CreateFile("\\\\.\\<SymlinkName>", ...);
DeviceIoControl(h, IOCTL_..., in, out);   // -> kernel primitive
```

Per-driver commands and use-cases, where publicly documented, are in
`entries/<sha256>.json` under `usage.commands` (LOLDrivers data).

## Primitive classes (what `capability_profile` means)

| Import(s) | Primitive gained |
|-----------|------------------|
| `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmGetPhysicalAddress` | Arbitrary physical memory R/W |
| `ZwMapViewOfSection`, `ZwOpenSection` | Section mapping → kernel memory access |
| `MmCopyVirtualMemory`, `MmCopyMemory` | Cross-process / kernel memory copy |
| `ZwOpenProcess`, `PsLookupProcessByProcessId`, `KeStackAttachProcess` | Read/write/terminate other processes (EDR killer pattern) |
| `ZwTerminateProcess` | Kill protected processes |
| `MmProbeAndLockPages`, `IoAllocateMdl`, `MmAllocateContiguousMemory` | Pin/map user buffers into kernel space |
| `ZwLoadDriver`, `MmLoadSystemImage` | Load further kernel code |
| `__readmsr`, `__writemsr` | Model-specific register access (CR4, LSTAR …) |
| `ZwSetSystemInformation`, `NtSetSystemInformation` | Kernel state manipulation |

`missing_probe_validation` in an entry = the driver calls
`ProbeForRead`/`ProbeForWrite` on **none** of its imports while exposing the
above — the classic unvalidated-`METHOD_NEITHER`-IOCTL smell.

## Detection guidance

- **Sysmon Event ID 6** (DriverLoaded): alert on hashes from
  `protection_feed.json` / `manifest.csv`.
- **Sysmon Event ID 4 / Windows Event 7045** (service installed): new
  `type=kernel` services created by non-system processes.
- **WDAC / HVCI vulnerable-driver blocklist**: the entries here that are
  not yet in Microsoft's list are exactly what the blocklist update process
  needs.
- **Device access telemetry**: `CreateFile` on unusual device symlinks
  followed by `DeviceIoControl` bursts.
- **Certificate intelligence**: flag loads where the signer subject is an
  obscure CA or a known-leaked cert (LOLDrivers `Signatures` data).

## Ethical/legal line

This catalog exists so defenders can block, detect, and audit — and so
researchers can report vulns to vendors. Installing these drivers on
systems you do not own, or using the primitives against production
machines, is illegal in essentially every jurisdiction.

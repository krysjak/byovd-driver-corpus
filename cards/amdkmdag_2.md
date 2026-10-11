# `amdkmdag_2.sys`

[Back to index](../README.md) · [Українська версія](amdkmdag_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C482A327377F028C8DBD7BE1FDFD32C0A9F1F2E21C8BC3BE5F0F07DE14A3AFA4` | `21F53AA5DB675199332C559A26755B304FD8521D` | `45FA307026081AA1F8353AC93F6B80DD` |

## Metadata

- **Filename:** `amdkmdag_2.sys`
- **Size:** 100367472 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** ATI Radeon Family
- **Description:** ATI Radeon Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 165

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

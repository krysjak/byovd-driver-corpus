# `igdkmd64_3.sys`

[Back to index](../README.md) · [Українська версія](igdkmd64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `896A0CFE0138CC75955E34E641CF692F9A5314D093C03EAD4B01ACDF3719719F` | `BCE52BCAD0FB0DEF978867D0D173FB81E4389909` | `3A70558AEA73E8B558C8C01E5D6AC69D` |

## Metadata

- **Filename:** `igdkmd64_3.sys`
- **Size:** 40030272 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 170

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

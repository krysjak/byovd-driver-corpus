# `igdkmdn64_3.sys`

[Back to index](../README.md) · [Українська версія](igdkmdn64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9081A461469BCC71A72184DB7665F532030D9510564AC8F10473BBE36237E724` | `7EA0C0998938291898C0B5F9443CE3323F06B001` | `C5143248F5A26E76ADAA68E048797DD2` |

## Metadata

- **Filename:** `igdkmdn64_3.sys`
- **Size:** 53115072 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode New Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 180

## Capability profile

**Primitives:** `MDL allocation`, `arbitrary memory copy`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

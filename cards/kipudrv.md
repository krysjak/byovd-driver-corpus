# `kipudrv.sys`

[Back to index](../README.md) · [Українська версія](kipudrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1ADD63E519CE5F2D6C0CBF2EDA75BB988CEC78809D1EB3C5DDCFD86CDBA68067` | `BAE3B8A733CAAED638638DA17BD3D85F0F279EDA` | `2B3B8A3E64F5CE0DBF208EC5E5707782` |

## Metadata

- **Filename:** `kipudrv.sys`
- **Size:** 832184 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD IPU Driver
- **Description:** AMD IPU Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `kipudrv_win10.sys`

[Back to index](../README.md) · [Українська версія](kipudrv_win10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B5B26BE2BDE2FE31804F4493D483CA8B316081814D67961FBB8BC687E95721CE` | `EF9684DE1891BB43C178FD003AC6867C33907FC6` | `3075BF488B3C5B695DA155B20AE6B8A9` |

## Metadata

- **Filename:** `kipudrv_win10.sys`
- **Size:** 828520 bytes
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

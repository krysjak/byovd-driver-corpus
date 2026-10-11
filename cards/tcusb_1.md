# `tcusb_1.sys`

[Back to index](../README.md) · [Українська версія](tcusb_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5F645C229C4F7E177AE8B1126FEDE1D9BF3F436F9EAEDDC3804A41D9AF6A5BB4` | `976EF125DA4EE8C5A3D212AC47772EE8660AE3D4` | `9BAAD1DB231539E7F786A074BC0B5264` |

## Metadata

- **Filename:** `tcusb_1.sys`
- **Size:** 63848 bytes
- **Architecture:** 0x8664
- **Company:** AuthenTec, Inc.
- **Product:** TouchChip USB Kernel Driver
- **Description:** TouchChip USB Kernel Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

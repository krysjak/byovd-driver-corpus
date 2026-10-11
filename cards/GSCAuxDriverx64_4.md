# `GSCAuxDriverx64_4.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FC4C3AC66F00DE8A84CF7549A566102BA288493540D301DF5EF9123F7C22962A` | `378CDD5167E11C89942B95171DA772CB37B81D38` | `D0F566B3C96EAD4B576C01D6989A77D0` |

## Metadata

- **Filename:** `GSCAuxDriverx64_4.sys`
- **Size:** 79992 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Description:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

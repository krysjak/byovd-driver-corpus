# `GSCAuxDriverx64_7.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A7FD4FEF369E14528AA6E8012E0268BB6F3E4582BFCAC9096A88812E879CA24` | `B4966501901A1A0A93D79AC92D4D40C29701A50B` | `6222F1237337D6930E897E2FB12B6E79` |

## Metadata

- **Filename:** `GSCAuxDriverx64_7.sys`
- **Size:** 109248 bytes
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

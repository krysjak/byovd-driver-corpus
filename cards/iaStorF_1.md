# `iaStorF_1.sys`

[Back to index](../README.md) · [Українська версія](iaStorF_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C2858590436EEDDE029C5448AEC3ACBB1C0FCED23F305302BAF831C6EC1654A` | `649E6520B7EF03F772C5F2E7206D305E3F42F8FE` | `B9D5AE799CB622C144AE5399C55EF29B` |

## Metadata

- **Filename:** `iaStorF_1.sys`
- **Size:** 28008 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Rapid Storage Technology Filter driver 
- **Description:** Intel Rapid Storage Technology Filter driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

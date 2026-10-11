# `iaStorA_2.sys`

[Back to index](../README.md) · [Українська версія](iaStorA_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `520399E73B9F6460378768CE75976F91CE024A6111C7238A5D1D6E154532F60F` | `AAF874B6F4A72677ACFA5A515BA60F6E7217FF8D` | `6C76ED95D0572FB0BD0FA7C55F5930F2` |

## Metadata

- **Filename:** `iaStorA_2.sys`
- **Size:** 1992192 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x86
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `iaLPSS2_SPI.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9E6873BFFFA91D33FC59C481068AE9E8EDCE108F0FADD82E46375CF7DF765AD3` | `883F7D5D46E0D74FFA2DADC6687EFF6DA7D09094` | `291F56FDA7E4A53E3F14D9C3BEB8996B` |

## Metadata

- **Filename:** `iaLPSS2_SPI.sys`
- **Size:** 159352 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO SPI Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

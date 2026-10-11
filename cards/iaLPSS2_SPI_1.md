# `iaLPSS2_SPI_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4D3FB8CEBF0D5F1A4A24EC80126BC4E68EDF289C3683FD6C93E8B3048EC69015` | `B1D5DB71CFCE1E68421B034184F453142FBF633A` | `0872F31ACD7B6EF9FFD48F2CBCF67FDD` |

## Metadata

- **Filename:** `iaLPSS2_SPI_1.sys`
- **Size:** 156768 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO SPI Driver v2
- **Signature:** signed
- **Source:** `oem:hp`
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

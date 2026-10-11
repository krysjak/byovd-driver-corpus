# `iaLPSS2_SPI_TGL_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_TGL_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F8586E68B8555753E16CBECE50345716197C81535A69F02C486653CB3CCAC2AD` | `D590007405714DDC9075E00D9A89968B9E8A9C04` | `AAB13970FA31A7B83B6AAED663DC7235` |

## Metadata

- **Filename:** `iaLPSS2_SPI_TGL_1.sys`
- **Size:** 158352 bytes
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

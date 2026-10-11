# `iaLPSS2_SPI_ICL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_ICL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B66688534832295A9A7A5AE582DB9F0B1B7FADCD37022BBB682670F3633242D` | `C3A821A6F587A2123E76A5E273A2C65172977DD3` | `D709D4B211A65B870709BDA81FA7E10B` |

## Metadata

- **Filename:** `iaLPSS2_SPI_ICL.sys`
- **Size:** 160024 bytes
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

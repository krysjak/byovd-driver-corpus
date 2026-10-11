# `iaLPSS2_SPI_MTL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_MTL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BAD7E42C8D94B7AE680DA5161EF8454E77F526635763D04E6B3978152DAE637` | `A3611BFDEBE9F9B344E9025508D7B3603D46C467` | `B3A733E3A69FDDCBB5B074CD8C7F6AC8` |

## Metadata

- **Filename:** `iaLPSS2_SPI_MTL.sys`
- **Size:** 163328 bytes
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

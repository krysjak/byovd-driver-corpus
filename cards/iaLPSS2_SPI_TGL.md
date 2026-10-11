# `iaLPSS2_SPI_TGL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_TGL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D3588E5656C2CE9E51BF9EC6FE0B25807BA9762017DFE142A5FF4DC4CA85D7DB` | `E8579FA88B3B9D2BEAAEBBE1EAE86129FE959974` | `933707288E48D76229F463BEE9DAA60B` |

## Metadata

- **Filename:** `iaLPSS2_SPI_TGL.sys`
- **Size:** 155808 bytes
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

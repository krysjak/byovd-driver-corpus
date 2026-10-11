# `iaLPSS2_I2C_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2A6866C3FEAD33BC5C850CFBE8DA064AF3F9D759FCD84308A25BE12B85019D25` | `63C233A4E3491164066F66766A49A0072DC7719C` | `5F5457824ABCBD53898945983330F515` |

## Metadata

- **Filename:** `iaLPSS2_I2C_CNL.sys`
- **Size:** 196360 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
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

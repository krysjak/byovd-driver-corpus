# `iaLPSS2_UART2_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DC8D280A746872D0C7F23A53199F48DA5B8CC48BE048F8608ED3B5AF5EFC22AE` | `4AF625AA065F5C09EF8B3D94E616CC1C5C259769` | `7C9DAA00F31AE0E09292AF0704038705` |

## Metadata

- **Filename:** `iaLPSS2_UART2_CNL.sys`
- **Size:** 305928 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO UART Driver
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

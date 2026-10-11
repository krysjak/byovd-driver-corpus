# `iaLPSS2_UART2_ADL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_ADL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A7AE12D6AFE9CFEA7EFC636B37A1FF7B0E3190DF64DA9C5BBD66272E461C0E0E` | `31EEDE1E78C53ACD645B0775F84867E70153915D` | `8FC8158496B4C3BA378BA7A1F96DC6E1` |

## Metadata

- **Filename:** `iaLPSS2_UART2_ADL.sys`
- **Size:** 329320 bytes
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

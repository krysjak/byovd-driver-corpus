# `iaLPSS2_UART2_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B041B9A5281F1841730F6AA5960F4C4EE3D7A4ACF807562D646EBF6F2838B81F` | `E99BE7D2A185A287302F0C65E2AC597B81669AA2` | `010A4E99410D8C557099A4568B79A4FB` |

## Metadata

- **Filename:** `iaLPSS2_UART2_1.sys`
- **Size:** 305760 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO UART Driver
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

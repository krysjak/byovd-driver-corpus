# `iaLPSS2_GPIO2_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4D834A49DCB4F87655E01F46A70FF1206AA67EFD06C23189968C5848727CD30A` | `9F14DB10205A2C2C2FD47DB218583D5258B84441` | `E64E3C5E00F3ACEF92986379167A85FB` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_1.sys`
- **Size:** 128608 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
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

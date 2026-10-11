# `iaLPSS2_UART2_ICL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_ICL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D080F7BD9D0FACC1EC20626FE5F58EB90C6FA854BEBC96989AD043AC61C8304D` | `A7C1930AA72D24253E21493C73CD856743E98BBC` | `4585D72F9A720A9935F9861613DC322D` |

## Metadata

- **Filename:** `iaLPSS2_UART2_ICL.sys`
- **Size:** 312600 bytes
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

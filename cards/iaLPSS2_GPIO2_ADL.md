# `iaLPSS2_GPIO2_ADL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_ADL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `818D4E3228A9A52EE86FADE0EF07686FB625F5747F8A3DCBCA7A40AFF2C5C3E8` | `D27F254488A0387F6C41CA5EE8B431D00C2603AE` | `974D04F22B23B9BAEF565340697F8B55` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_ADL.sys`
- **Size:** 150616 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
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

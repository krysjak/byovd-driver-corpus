# `iaLPSS2_GPIO2_ICL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_ICL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D981363E6B53D13960AB6C5587A2439A104864BA2B604D5EFDA049AB504CC782` | `0F4E9AD3B28DFF27D4A594F45DD1E807E50A33BB` | `A58D5A4BBFF60873E57E5D4AAB9EEB2B` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_ICL.sys`
- **Size:** 132872 bytes
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

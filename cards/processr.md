# `processr.sys`

[Back to index](../README.md) · [Українська версія](processr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D0B16F8BB169B8E2F2D796E7EC7AB1CADC1E9B4C61EB8B99CA719DA1A17B4441` | `80F2693197455CB80126F80FDA5A276CB6E21B33` | `766D5536999FC695B469F88BD4D2F406` |

## Metadata

- **Filename:** `processr.sys` (Identical copies: `processr_2.sys`)
- **Size:** 275928 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Processor Device Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

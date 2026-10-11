# `iaLPSS2_GPIO2_MTL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_MTL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA498023B592719F8E4757557012D9068CAB84941015295DC694DFA26696E76B` | `811CD89EF4D4A18D74F0C5A688180C3E056C4F88` | `8B9C2D532FF25533A67B91073BCDB908` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_MTL.sys`
- **Size:** 176128 bytes
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

# `iaLPSS2_GPIO2.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D6361B5FF49DC4490895698AC715A0FBF8DF304464E3FFF56DE210DC63B30A9` | `3D4B54F9C40EF0A970F0B55B182948DCF6FF82D4` | `9FE4CB3929DFC9571756B45A9988FF71` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2.sys`
- **Size:** 113272 bytes
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

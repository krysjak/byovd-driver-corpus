# `iaLPSS2i_GPIO2_GLK.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_GPIO2_GLK.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `71FDC25244298D62A335769D6ED43394C33FBD8DB05AA54CA924A2977F37858F` | `27406A360E030CB321D0F4F77A1C53D7BCC9B53E` | `8D3E3C431367E3BA632B4396CA662E1A` |

## Metadata

- **Filename:** `iaLPSS2i_GPIO2_GLK.sys` (Identical copies: `iaLPSS2i_GPIO2_GLK_1.sys`)
- **Size:** 96256 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
- **Signature:** unsigned
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

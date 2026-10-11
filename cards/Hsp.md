# `Hsp.sys`

[Back to index](../README.md) · [Українська версія](Hsp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `54A4374AE70C31479C3BFC6FA22B9051880953E81AE93E2F560CFF170400BF89` | `8113DF48ED763C6DB0AFF9725E2590D2929F8182` | `E8B278887952F3421E2507171D603D9C` |

## Metadata

- **Filename:** `Hsp.sys` (Identical copies: `Hsp_1.sys`)
- **Size:** 124400 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** HSP Device Driver
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

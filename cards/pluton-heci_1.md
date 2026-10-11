# `pluton-heci_1.sys`

[Back to index](../README.md) · [Українська версія](pluton-heci_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `688019578FB97E91321249CF55B6C848CC679C8C5B8B465F89F2D360BA3B115A` | `1039C75FCB1716FCC442F01368B6EBC71C1BD07C` | `A671486F71AC22D8C5B5256BDED157E3` |

## Metadata

- **Filename:** `pluton-heci_1.sys` (Identical copies: `pluton-heci_2.sys`)
- **Size:** 79256 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Pluton HECI Device Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 90

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

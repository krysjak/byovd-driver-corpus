# `mpsdrv.sys`

[Back to index](../README.md) · [Українська версія](mpsdrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D640F00F5E152782906D443981F7577DBAA1960058E27B7683BA029182F5A220` | `A3904FC35F0C5925DEB32A62D26EED1A649A23D5` | `B2A5127A97FF55134CADF6543F85836B` |

## Metadata

- **Filename:** `mpsdrv.sys`
- **Size:** 114688 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Protection Service Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

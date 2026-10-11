# `UfxChipidea.sys`

[Back to index](../README.md) · [Українська версія](UfxChipidea.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C4E58AE7833097F4AB1264A9888F3790D819BC5F29A2BAD268F8DEC8730BF070` | `139084DFA88F2CC488F3D3A392C5A53E370D7B36` | `93064B010CDBEE52A44F6D55514B65F9` |

## Metadata

- **Filename:** `UfxChipidea.sys`
- **Size:** 140592 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** UFX Chipidea Client Driver
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

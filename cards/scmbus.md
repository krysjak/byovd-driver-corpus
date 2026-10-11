# `scmbus.sys`

[Back to index](../README.md) · [Українська версія](scmbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `167D74D8F1A0815409A6A315FA55BB416FE8584280A89393A98ACA1A6A245327` | `792C707AC99F780B7B72F2840B164A317A4C83FA` | `036139D75294C8DA95D212CB5E543132` |

## Metadata

- **Filename:** `scmbus.sys` (Identical copies: `scmbus_2.sys`)
- **Size:** 259576 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storage Class Memory Bus Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

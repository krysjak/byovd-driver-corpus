# `errdev.sys`

[Back to index](../README.md) · [Українська версія](errdev.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E3FA480F869C3E1D6BF2E78CB7665F19D5F399A8D359FFFA4B71805DAFEB9A` | `F224C163892665E4D85E009047C4761E175692B4` | `A96F659CB5EE6D897E16825BD255413F` |

## Metadata

- **Filename:** `errdev.sys` (Identical copies: `errdev_1.sys`)
- **Size:** 53248 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Error Device Driver
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

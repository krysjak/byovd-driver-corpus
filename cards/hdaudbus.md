# `hdaudbus.sys`

[Back to index](../README.md) · [Українська версія](hdaudbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B2C4E15010266558096F2B5AE57550601D6F70ACC054E8603E702D349DDEBB4` | `F49A5278C26227E7E3E4A1743462A40BE4545F5B` | `0AA5D597380B2585FDAC7E53C0660F30` |

## Metadata

- **Filename:** `hdaudbus.sys` (Identical copies: `hdaudbus_1.sys`)
- **Size:** 204800 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** High Definition Audio Bus Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

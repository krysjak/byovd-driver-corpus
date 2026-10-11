# `vpci_2.sys`

[Back to index](../README.md) · [Українська версія](vpci_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F7D0D46266582D5C7ACEA29CC7D75D1C4A28A237DF3AD34E43BE9CD1EA78F1D1` | `297393A4002266146A055761ED2468E58CAECE7A` | `982441187C93E352D2EFF561BC9979DE` |

## Metadata

- **Filename:** `vpci_2.sys` (Identical copies: `vpci_3.sys`)
- **Size:** 161184 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Virtual PCI Bus
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

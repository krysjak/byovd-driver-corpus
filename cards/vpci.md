# `vpci.sys`

[Back to index](../README.md) · [Українська версія](vpci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5582D06D0CAE7C1E2D4DF659824EC9E7434C64B3F17738EF723C82DB08F389EC` | `C08586F70D99BB8B3D5556589FAC43DE73E60B1C` | `80C6399EA81B6736620CDE235126CAB7` |

## Metadata

- **Filename:** `vpci.sys` (Identical copies: `vpci_1.sys`)
- **Size:** 169464 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Virtual PCI Bus
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

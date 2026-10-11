# `intelpep_2.sys`

[Back to index](../README.md) · [Українська версія](intelpep_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `865F9566A0F0C5E23C256DB20CEBBF258204940F722391A1B378FA51718418D2` | `110E7C5F1682769F10639A79DC7AC804118F4767` | `910E484459B18A7E81831016B66FD716` |

## Metadata

- **Filename:** `intelpep_2.sys` (Identical copies: `intelpep_3.sys`)
- **Size:** 641424 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Intel Power Engine Plugin
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

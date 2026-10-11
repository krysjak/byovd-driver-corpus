# `pcmcia.sys`

[Back to index](../README.md) · [Українська версія](pcmcia.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `505F1106FCB85C22FB2B68B8EBDC945A0C361EC12F8FBC4FF2C412D58BB785D9` | `B5F8CAA16B285023B3E8688CEB1E7B473D2A4DBB` | `D8A0E2B1330FFC122B9B72B0CB2A17C1` |

## Metadata

- **Filename:** `pcmcia.sys` (Identical copies: `pcmcia_1.sys`)
- **Size:** 156992 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** PCMCIA Bus Driver
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

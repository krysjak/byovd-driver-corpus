# `pluton-heci.sys`

[Back to index](../README.md) · [Українська версія](pluton-heci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `534A771165BDA8CB30BC856F69ACF624B98B810196873AE3306FCB6703A3CA09` | `9B0F6FC1C2BBB5BEA2FBAD2505A811C259060F29` | `8D3AAA6796553ED6952BCF079E5ADCE9` |

## Metadata

- **Filename:** `pluton-heci.sys`
- **Size:** 95704 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Pluton HECI Device Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

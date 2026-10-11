# `UcmUcsiAcpiClient.sys`

[Back to index](../README.md) · [Українська версія](UcmUcsiAcpiClient.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3931AC4925B70D4D84B36610C522DFBA373E98416FFA65CD6B468782AEB76B50` | `D8B5CED2715C8A69BC46CCE047106815505E37C8` | `349122C1D5464C4D2123DA5312C19760` |

## Metadata

- **Filename:** `UcmUcsiAcpiClient.sys` (Identical copies: `UcmUcsiAcpiClient_1.sys`)
- **Size:** 77824 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** UCM-UCSI ACPI Client Driver
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

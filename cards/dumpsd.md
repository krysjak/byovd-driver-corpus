# `dumpsd.sys`

[Back to index](../README.md) · [Українська версія](dumpsd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `923F7B0ADDAC1717C87E47CADE65938D42985A7B0EF799D0B3ABFA8A1F3941BA` | `93660116645B28867123720E2BCAF9906F123560` | `B5105BC2A71948859D4BEA420128B852` |

## Metadata

- **Filename:** `dumpsd.sys` (Identical copies: `dumpsd_1.sys`)
- **Size:** 234960 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SD Crashdump Port Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

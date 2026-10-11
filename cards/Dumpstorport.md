# `Dumpstorport.sys`

[Back to index](../README.md) · [Українська версія](Dumpstorport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64C11EB22AD2F95060A7918CFEF9D512C7E4143EFA16260BC978C7A3EE1A7B0C` | `B76B1B5C6991A0BAB5D12630778BB623AAA2F40A` | `1032E83839E2DDE72D5B30CD64AF7D4C` |

## Metadata

- **Filename:** `Dumpstorport.sys`
- **Size:** 108008 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storport Dump Driver
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

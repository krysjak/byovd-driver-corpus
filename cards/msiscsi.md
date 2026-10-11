# `msiscsi.sys`

[Back to index](../README.md) · [Українська версія](msiscsi.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E8FE743F63E439EE79CA6625B26A4936B719CD61D3FCC67987E06DAE7733CF17` | `A70093428A22769BDEE1DD30B3857B5B330D6A66` | `3295AC755E7A6CA887ED71430826D905` |

## Metadata

- **Filename:** `msiscsi.sys` (Identical copies: `msiscsi_1.sys`)
- **Size:** 333240 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft iSCSI Initiator Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

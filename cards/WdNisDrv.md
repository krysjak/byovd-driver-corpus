# `WdNisDrv.sys`

[Back to index](../README.md) · [Українська версія](WdNisDrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `66A19E397D0709556CEF79886CA8562329ACEDCE7B6F63970A61953E566B3D25` | `78790D7357EA894FD4067F6468FFD9624DA6545E` | `168B3BB22E48AC4FF592BDEE8CEF5D22` |

## Metadata

- **Filename:** `WdNisDrv.sys`
- **Size:** 103816 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Defender Network Stream Filter
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

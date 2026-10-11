# `spaceport_1.sys`

[Back to index](../README.md) · [Українська версія](spaceport_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E26F516FA887E17143A7D53A047B2BF180DE704EFD63A45A41A409BA816D8ED7` | `64C76D8F29E75ED4E5FCC047687EF592A10C13EA` | `0835509BD13E767E9D645C4F9CBEF179` |

## Metadata

- **Filename:** `spaceport_1.sys` (Identical copies: `spaceport_3.sys`)
- **Size:** 1021344 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storage Spaces Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

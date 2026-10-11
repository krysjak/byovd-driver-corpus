# `volsnap.sys`

[Back to index](../README.md) · [Українська версія](volsnap.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `48F93F83AD24CA500586223CCD8C76B200574F0F9A9AE6100DA60171C87A9CB9` | `EE7596431E66A4CC199D39BC221C755518D93F35` | `8F9CA5327986717A161CBD0EB1ABAA0C` |

## Metadata

- **Filename:** `volsnap.sys`
- **Size:** 542208 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Volume Shadow Copy driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

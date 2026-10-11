# `mskssrv.sys`

[Back to index](../README.md) · [Українська версія](mskssrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9C0E1552EA6EA826CFB709781FEC95E08195698B7881A2DD7A96590D5DFE88A5` | `4A7170CD8D7DD041CF56D755B09D4B389409D9B6` | `530C41B7BDD1A185E88F8926A2B4D93F` |

## Metadata

- **Filename:** `mskssrv.sys`
- **Size:** 77824 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** MS KS Server
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `spaceport.sys`

[Back to index](../README.md) · [Українська версія](spaceport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `76F885B1FF347958E0EF009A0D1FAE5F532DC15BA8119A5F61051180D4161B8D` | `1E3F841AF90644F54F2DB1C21AE450C953C77AE5` | `99588262F38CEFBAE01E3D617B3A420E` |

## Metadata

- **Filename:** `spaceport.sys` (Identical copies: `spaceport_2.sys`)
- **Size:** 1021416 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storage Spaces Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

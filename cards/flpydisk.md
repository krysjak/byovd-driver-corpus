# `flpydisk.sys`

[Back to index](../README.md) · [Українська версія](flpydisk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2B920DCEDB85453F619C599083046B6DE8670886AB2D13593771DFADCCEBBEB2` | `7989EAAE9A4BD54D374CD7D4E213ED33528FA4B8` | `27FDBA8F9DC034A82735E6F28768377C` |

## Metadata

- **Filename:** `flpydisk.sys` (Identical copies: `flpydisk_1.sys`)
- **Size:** 65536 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Floppy Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

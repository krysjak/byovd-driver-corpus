# `volmgr_2.sys`

[Back to index](../README.md) · [Українська версія](volmgr_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `31A1A8FA2A9419F3E6DE852B3E11417921B27861FE6127363466FD2C936B4B3F` | `291ACF15DF64A2271573D6AC54E2269A1B51824B` | `1DD7B493136E6F8E5852A72A39801D79` |

## Metadata

- **Filename:** `volmgr_2.sys` (Identical copies: `volmgr_3.sys`)
- **Size:** 132480 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Volume Manager Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

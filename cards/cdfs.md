# `cdfs.sys`

[Back to index](../README.md) · [Українська версія](cdfs.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C6EE866166E1019C5D9560E2C34AA4203D0C40FCB8EAC50C5A31223C08A0C334` | `BE14A53B8A83A2E837D1E3054CDA15E076C31F5D` | `7343300029A25828E41B5E37279F62E7` |

## Metadata

- **Filename:** `cdfs.sys`
- **Size:** 131072 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** CD-ROM File System Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

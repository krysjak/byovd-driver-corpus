# `AppVStrm.sys`

[Back to index](../README.md) · [Українська версія](AppVStrm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3A3E7226604BBB69EDE8BC8A4FDE61F59922B8C795442D7F05A8077C11A2FA0C` | `6E4B1411D8E3D91D72CE2C55C3589801511DD567` | `C7415379FB9F8DE40CCCC1E9162002FE` |

## Metadata

- **Filename:** `AppVStrm.sys`
- **Size:** 177456 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Application Virtualization Streaming Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

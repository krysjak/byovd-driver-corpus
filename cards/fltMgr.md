# `fltMgr.sys`

[Back to index](../README.md) · [Українська версія](fltMgr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `76B7AB968A533637E4F1D8BE1CA66B0231CE1C3048C3127549CAEE15A79D5AC6` | `1472BB0F8EFD0391F93EF9EE3485DCEEACD64615` | `EA06C19624940A7FEAB6A9B35CCBCD86` |

## Metadata

- **Filename:** `fltMgr.sys`
- **Size:** 611792 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Filesystem Filter Manager
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

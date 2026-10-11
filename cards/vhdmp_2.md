# `vhdmp_2.sys`

[Back to index](../README.md) · [Українська версія](vhdmp_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1046DB0C243ED7011ED907F9914C7F34574431F3BFAA0E9DE5CBCDD57AB9BA09` | `62DBBBCFA9D06CB16A8A6432AF983C2A92FBEEF7` | `B847F52622379A997CC6DBB280CA43BB` |

## Metadata

- **Filename:** `vhdmp_2.sys` (Identical copies: `vhdmp_3.sys`)
- **Size:** 1058200 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** VHD Miniport Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 110

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

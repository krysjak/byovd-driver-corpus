# `vhdmp.sys`

[Back to index](../README.md) · [Українська версія](vhdmp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `690C256F6C5045ADBEB68452A0147F802A89B3BCD49532CAA26C89654113C739` | `BC44D9A418417D89469C9E7CA92494D387253A75` | `150CA9EDAC79C3EA1D3333FE35624763` |

## Metadata

- **Filename:** `vhdmp.sys` (Identical copies: `vhdmp_1.sys`)
- **Size:** 1058288 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** VHD Miniport Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

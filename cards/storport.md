# `storport.sys`

[Back to index](../README.md) · [Українська версія](storport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6833A7666C673E0A80AFAD0D3889C5DB86226F51B65C1E97F57E19393A42B949` | `498380C05A4A1D4E09C5833B2946B3C9F4E96BEC` | `FD5D2482CC212AE920536B30AB23EAD7` |

## Metadata

- **Filename:** `storport.sys`
- **Size:** 2602496 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Storage Port Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwLoadDriver`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

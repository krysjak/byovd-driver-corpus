# `scsiport.sys`

[Back to index](../README.md) · [Українська версія](scsiport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0644B97F847EF3F1C9CB053D50BE73F043E59278D3748B84130E459C1B39A83A` | `29BC689219960B096E290B4B13CA6CFD6F831329` | `8F3D558B51BF137B516FCC8134AC2964` |

## Metadata

- **Filename:** `scsiport.sys`
- **Size:** 226736 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SCSI Port Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

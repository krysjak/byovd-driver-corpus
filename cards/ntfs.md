# `ntfs.sys`

[Back to index](../README.md) · [Українська версія](ntfs.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `24B023140A6D162DB3FE0D701109FC0BE4FDD9EC65E1C40522934AE3CC0A28C6` | `7D51FCE87B96A2F32DCDCC64C3D23EB4754AB7CA` | `7BE24DA2E71B3BED7BBCE3C2AC7D5B6B` |

## Metadata

- **Filename:** `ntfs.sys`
- **Size:** 3556856 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NT File System Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

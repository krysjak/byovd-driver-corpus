# `dxgmms2.sys`

[Back to index](../README.md) · [Українська версія](dxgmms2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27898B834168483FC83E93294C4C6CDB4908E3056FC127F0876422F9F9FEAF41` | `8481B1404227D2FCF20834AF5004CFBE4F4AA4E5` | `3E16C3050CA6FAE7F93710FA61DB06AE` |

## Metadata

- **Filename:** `dxgmms2.sys`
- **Size:** 1197528 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** DirectX Graphics MMS
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

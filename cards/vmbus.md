# `vmbus.sys`

[Back to index](../README.md) · [Українська версія](vmbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3CC7F47ADAAE3840FD4DA88185F3E10A9F783E04ED9ABC8104923D22FCF1F2BA` | `5E2DF3CAE9EF52EB354FC357303CB5D520F1F576` | `E82D06B490EAABE0E9ABC93A0C935841` |

## Metadata

- **Filename:** `vmbus.sys` (Identical copies: `vmbus_1.sys`)
- **Size:** 210424 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Hyper-V Virtual Machine Bus Child Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

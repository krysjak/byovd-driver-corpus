# `Vid.sys`

[Back to index](../README.md) · [Українська версія](Vid.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0E4A4E121BFF67928BDB23241CA21A7594241E45BF4F9D8C560754868ECA4B57` | `4B0AA20CC077D46886A706159D4528A2CABCCF8E` | `4067EDB06E47E82388E91A3843210BA8` |

## Metadata

- **Filename:** `Vid.sys` (Identical copies: `Vid_1.sys`)
- **Size:** 910816 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Hyper-V Virtualization Infrastructure Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `cross-process memory copy`, `page locking`, `physical memory mapping`, `process address-space attach`, `process termination`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyVirtualMemory`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

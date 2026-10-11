# `Vid_2.sys`

[Back to index](../README.md) · [Українська версія](Vid_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7F90AADC25CA83DED17A3DE262A64C6DEFD6EE6E50C5ED71F86F7D0B9CC3AC91` | `5D85BD805F7B818343BCD7C225F7C36D82E9A058` | `F6B66498AC898D43B083576B411529EB` |

## Metadata

- **Filename:** `Vid_2.sys` (Identical copies: `Vid_3.sys`)
- **Size:** 914840 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Hyper-V Virtualization Infrastructure Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Live system
- **Score:** 155

## Capability profile

**Primitives:** `MDL allocation`, `cross-process memory copy`, `page locking`, `physical memory mapping`, `process address-space attach`, `process termination`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyVirtualMemory`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `VBoxSup.sys`

[Back to index](../README.md) · [Українська версія](VBoxSup.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `55785D57968FD427D7332765D1D811832E8A43DF12668BE4C86F2B7BD18EFD55` | `EA20C5FB099CD005F4F19440B09C738912DE62C2` | `79BE1DEF92DC68B4178999C0CB01D958` |

## Metadata

- **Filename:** `VBoxSup.sys` (Identical copies: `VBoxSup_1.sys`)
- **Size:** 1057120 bytes
- **Architecture:** 0x8664
- **Company:** Oracle and/or its affiliates
- **Product:** Oracle VirtualBox
- **Description:** VirtualBox Support Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `system information set`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

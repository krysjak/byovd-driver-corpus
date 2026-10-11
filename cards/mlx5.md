# `mlx5.sys`

[Back to index](../README.md) · [Українська версія](mlx5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `453AD7F8590ADB357405D6DEEC5F868BA4B09AA351D4ABED64EAC6CF0B7754F9` | `115E6AF6AF6A8738CA15DF13344FE3770BE409DE` | `622726E4BC437E20CA689CD9F81E3D03` |

## Metadata

- **Filename:** `mlx5.sys`
- **Size:** 2433440 bytes
- **Architecture:** 0x8664
- **Company:** Mellanox
- **Product:** OpenFabrics Windows
- **Description:** Mellanox ConnectX Adapter NDIS driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `WUDFRd.sys`

[Back to index](../README.md) · [Українська версія](WUDFRd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `989F0C323E826653BFA0F3DD6EEB72621D7DF75BC0FA1C6DDFB5229431C39B0B` | `7FD1773780833D424926036A4F1BDA88A687D15E` | `910F0109DC99FFC11725688ECFC64545` |

## Metadata

- **Filename:** `WUDFRd.sys`
- **Size:** 411096 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Driver Foundation - User-mode Driver Framework Reflector
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

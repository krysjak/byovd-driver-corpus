# `rdbss.sys`

[Back to index](../README.md) · [Українська версія](rdbss.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6817A01FAA09F7CF11F6745DA584CC5667A4616522744B78E6A3D77559E57F48` | `E0F56A8C42A8DF847837767135BF8A7CF0F68DF7` | `B7AFAFFF83CCCD6405AEAB733D606E44` |

## Metadata

- **Filename:** `rdbss.sys`
- **Size:** 566760 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Redirected Drive Buffering SubSystem Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

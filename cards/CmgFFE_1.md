# `CmgFFE_1.sys`

[Back to index](../README.md) · [Українська версія](CmgFFE_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `29867E7044AB9C85C4AB99CB49DADFB8E40321873D4A25C8FBAEF8D368797DA2` | `14F3B912E512ABB0F3D4681C154E85F3E715209B` | `79555506F700F489B4D9276540ED67F5` |

## Metadata

- **Filename:** `CmgFFE_1.sys`
- **Size:** 476384 bytes
- **Architecture:** 0x8664
- **Company:** Dell Inc.
- **Product:** Dell Data Protection Encryption
- **Description:** Credant File & Folder Encryption Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

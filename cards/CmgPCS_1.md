# `CmgPCS_1.sys`

[Back to index](../README.md) · [Українська версія](CmgPCS_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4DD31A1972C2FD4DDFDB2CFAD916603DE4EF9D2179827F55847FA1A24B0E4E62` | `58F362D582E908D0277F5F2F077923B418AA7201` | `DF960F98D039CCD7BF13872A36640FFD` |

## Metadata

- **Filename:** `CmgPCS_1.sys`
- **Size:** 159456 bytes
- **Architecture:** 0x8664
- **Company:** Dell Inc.
- **Product:** CmgPCS.sys (64b,rls)
- **Description:** Port Controls Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 110

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

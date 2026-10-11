# `amdfendr_1.sys`

[Back to index](../README.md) · [Українська версія](amdfendr_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `28ED50420493AAAB06D74159F795788B0B5AB9107E247597C8A4629B214DBBF7` | `E8BD8B951B6FEDE2DBCFA3AD16D26D7DE6AE4E72` | `978D3CD0BE776BCB84B0AB742F023A63` |

## Metadata

- **Filename:** `amdfendr_1.sys`
- **Size:** 367312 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD Driver
- **Description:** AMD Crash Defender
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

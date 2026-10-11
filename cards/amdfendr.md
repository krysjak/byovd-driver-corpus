# `amdfendr.sys`

[Back to index](../README.md) · [Українська версія](amdfendr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `145BE5CFBC40DA8DB78C2AC4DAF921B00ADB27B62072B58B13794C229FDFB758` | `0088E9A1877F4AF91BE0E16D63021CEAE846439C` | `7AA87C1737A3F707586050304CCE6B91` |

## Metadata

- **Filename:** `amdfendr.sys`
- **Size:** 375192 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD Driver
- **Description:** AMD Crash Defender
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

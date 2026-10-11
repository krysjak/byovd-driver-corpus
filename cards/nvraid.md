# `nvraid.sys`

[Back to index](../README.md) · [Українська версія](nvraid.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DB769BF751D7B23FFCE8CC1BAABB335DA5DA15E06A845A049EB68C3791686FED` | `76772B44ABB64BB9437307E354A62AA83FB6201F` | `FB6829DFAE5EA01864C3CFE35452F7E3` |

## Metadata

- **Filename:** `nvraid.sys` (Identical copies: `nvraid_1.sys`)
- **Size:** 151472 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVIDIA nForce(TM) RAID Driver
- **Description:** NVIDIA® nForce(TM) RAID Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `amdfendr_2.sys`

[Back to index](../README.md) · [Українська версія](amdfendr_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6CC6D9CA61F86B96697D67DC373EA5FA3076AA43EC63EADFE26450F1F3E51883` | `3174825ABFF07AE084B474BFB8A3A769F85BA5F9` | `B9FA5F8958E815CA747832E09AA4C700` |

## Metadata

- **Filename:** `amdfendr_2.sys`
- **Size:** 147872 bytes
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

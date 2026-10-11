# `amdfendr_3.sys`

[Back to index](../README.md) · [Українська версія](amdfendr_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `922ADDF96DF6F28DFB66504F332FF31A219F4C8A237DDDC6E0A9386ABE09A20F` | `C46DF63C3E2727EA2FD5EC6460BACD56B9C894FC` | `46B8FE6E27D744739080CAD4F6A6AE16` |

## Metadata

- **Filename:** `amdfendr_3.sys`
- **Size:** 165848 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD Driver
- **Description:** AMD Crash Defender
- **Signature:** signed
- **Source:** `oem:hp`
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

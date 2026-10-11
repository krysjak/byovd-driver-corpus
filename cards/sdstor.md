# `sdstor.sys`

[Back to index](../README.md) · [Українська версія](sdstor.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D172AA216915C5976314DD1248F5AE47CCA54A1BD5084955E4F6640A111F6807` | `2609D99E5CAB548C99E9442001B134916D49DF77` | `A80EEE7632EBB394EEE37095DF329B2A` |

## Metadata

- **Filename:** `sdstor.sys` (Identical copies: `sdstor_1.sys`)
- **Size:** 140792 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SD Storage Class Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

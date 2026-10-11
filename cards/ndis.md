# `ndis.sys`

[Back to index](../README.md) · [Українська версія](ndis.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `221AE7328A432E9DA76A80C029596B1BEE0A06723A675E8DDB286B23CEDD685A` | `CD4471E4745D073A59BA3D93809096DFE13E82DF` | `12497FE12A8C5BB376E1EBB2DB4C31CC` |

## Metadata

- **Filename:** `ndis.sys`
- **Size:** 1828352 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Network Driver Interface Specification (NDIS)
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

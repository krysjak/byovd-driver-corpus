# `pmem.sys`

[Back to index](../README.md) · [Українська версія](pmem.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42DC33427358A149BC2CB6AFDAA03FB14D624BECF4B955AC5E27814FD4CD0F11` | `0858A1DDD0108977C522BBD584781FD131D3A357` | `952DA37086339D0E101C49EF4B545D1A` |

## Metadata

- **Filename:** `pmem.sys` (Identical copies: `pmem_1.sys`)
- **Size:** 185848 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Persistent memory driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

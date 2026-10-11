# `amdpsp.sys`

[Back to index](../README.md) · [Українська версія](amdpsp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3A93FDD9EB697AD67C765CACC307857B431032A7147DA47C1D7698D124C70615` | `094843FB26C506E5050AF4593B67579605B6146C` | `95402B931830D9BAC56AFE837D732A1A` |

## Metadata

- **Filename:** `amdpsp.sys` (Identical copies: `amdpsp_2.sys`)
- **Size:** 70144 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc. 
- **Product:** Advanced Micro Devices, Inc. amdpsp sys
- **Description:** amdpsp sys
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

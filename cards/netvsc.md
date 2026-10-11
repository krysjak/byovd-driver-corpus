# `netvsc.sys`

[Back to index](../README.md) · [Українська версія](netvsc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0E7FF5AE75372CED3A4640D890CEB0B5CA7E018CAD491A1F541F9A620B7A0D76` | `27B17EC69728DBC2595DD344DC5F6006288025F9` | `0CB1232CE2C03BC5CBE21C969037BAFB` |

## Metadata

- **Filename:** `netvsc.sys` (Identical copies: `netvsc_1.sys`)
- **Size:** 398808 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Virtual NDIS Miniport
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `sdbus.sys`

[Back to index](../README.md) · [Українська версія](sdbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C1E9481B69992105ADDA6D0E0AE577452F3CE8714CA3F5C7ECB55DF2D0897479` | `67FFA0AED6D88DA4B77C7F4CF7BEDADBA81F54F1` | `0BAA91899707D0A70A842D5C126FA698` |

## Metadata

- **Filename:** `sdbus.sys` (Identical copies: `sdbus_1.sys`)
- **Size:** 345560 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SecureDigital Bus Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

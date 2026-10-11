# `CmgPCS.sys`

[Back to index](../README.md) · [Українська версія](CmgPCS.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DA0F3F70DC51D0EAC03B4D279D95687D7E4C546C9820B146292E3E1BFFDE605E` | `EA0630194FFD036672C7BB86731AA92B305AC6B0` | `6D2DD3B75C463F3E6495E3D5206089E8` |

## Metadata

- **Filename:** `CmgPCS.sys`
- **Size:** 143968 bytes
- **Architecture:** 0x14c
- **Company:** Dell Inc.
- **Product:** CmgPCS.sys (32b,rls)
- **Description:** Port Controls Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 110

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

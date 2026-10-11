# `iaLPSS2_I3C_MTL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I3C_MTL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `25A22E16BFE19547CBDA604E6786582FBEDCBEBB94AAA9A5934E0F8778D28C1C` | `AB7038E5E575690BE0CAF01EC05FB72B3DA5CE97` | `A06B289C2A3A8AA9029C4FA18B714DAA` |

## Metadata

- **Filename:** `iaLPSS2_I3C_MTL.sys`
- **Size:** 156672 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I3C Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

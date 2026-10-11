# `Intel_NF_I2C_3.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C5AC16043AD6214DA945F6C16E29C31981915BC360554DAF13573570842D74AF` | `71E21371C033D22F66F8BECF02AEE60FFD39282B` | `64A87437654815CC35EA52CA0D09494C` |

## Metadata

- **Filename:** `Intel_NF_I2C_3.sys`
- **Size:** 223016 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) NF I2C Driver
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

# `Intel_NF_I2C_2.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `33F673B49AF9A32F9EC0513E5818A2052FF7C69B6F7920C6E678A693689F7EE9` | `A8451EA6CE2279326587F20F0671FF8AA006B5C2` | `FE6262341402DB50CBD3EB08DC3523D0` |

## Metadata

- **Filename:** `Intel_NF_I2C_2.sys`
- **Size:** 218056 bytes
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

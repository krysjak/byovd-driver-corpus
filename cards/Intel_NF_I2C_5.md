# `Intel_NF_I2C_5.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CC5EF39BB0FD1DCE1E256C9DA492B768F87CC8FEA9D5D49DF7AA35777BA8DD2B` | `0E3461BE51DA6503F974E80C205967C1E3DCC2D5` | `1DBE9E1637BE584101891113B8BDC28C` |

## Metadata

- **Filename:** `Intel_NF_I2C_5.sys`
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

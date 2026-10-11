# `iaLPSS2_I2C_TGL_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_TGL_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C89DC12EE639E08C329E5BD08FEE4FEEE20D9C0269955A768AE61A26EF5C82D8` | `92B2DC11185C33A4700267C4918F3D1275A650B6` | `B642B1BA09199021724DC09AD1E06481` |

## Metadata

- **Filename:** `iaLPSS2_I2C_TGL_1.sys`
- **Size:** 204440 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `amdi2c_3.sys`

[Back to index](../README.md) · [Українська версія](amdi2c_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `387811D57DEF06C9736D9F0BAB0DFB0F83DBAB19E5489BF9A6DCDCBD682DD8FE` | `3BC822EFF605EE91C84902A71659E1F52EAD9660` | `D0E26E590DE1424CCC4F77D1687049EF` |

## Metadata

- **Filename:** `amdi2c_3.sys` (Identical copies: `amdi2c_5.sys`)
- **Size:** 45568 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD I2C Controller Driver
- **Description:** AMD I2C Controller Driver
- **Signature:** unsigned
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `Intel_NF_I2C.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4B8BB8A77A6007F3BB6B3A4EB406C5A01441F405CFF778C09743F9B2988D44BA` | `6E92E66415548B37D717082A45819056972DAB9C` | `40C4D03F576A656CA0CB125041BE12A6` |

## Metadata

- **Filename:** `Intel_NF_I2C.sys`
- **Size:** 201440 bytes
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

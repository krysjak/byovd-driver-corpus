# `Intel_NF_I2C_1.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D02992E67A5B531A4DE899B565283EA0C54160F9AA87110BC472A163E7F065B1` | `4CC4B7A4E6BED6EC229B1133E5423B559AFF2EE3` | `81458491262AC01ECE1D581D6A3087B9` |

## Metadata

- **Filename:** `Intel_NF_I2C_1.sys`
- **Size:** 218040 bytes
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

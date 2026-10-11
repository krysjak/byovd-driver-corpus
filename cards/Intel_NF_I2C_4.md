# `Intel_NF_I2C_4.sys`

[Back to index](../README.md) · [Українська версія](Intel_NF_I2C_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `977057DF4EF3EDDA22BEC992FF519E6E871344B8B32E840FDCA8CC998D3EC7C1` | `AD9E7109DD78087043B9496F50F49D301E86848C` | `C9A7B3F036DC27892CF5FA8E38C02C94` |

## Metadata

- **Filename:** `Intel_NF_I2C_4.sys`
- **Size:** 222920 bytes
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

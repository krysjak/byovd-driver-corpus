# `TbtBusDrv_1.sys`

[Back to index](../README.md) · [Українська версія](TbtBusDrv_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `574E2C5A35E297BB0F2046526771A432D814B69930D3F0ED43EFBBDF4CD9AEB8` | `CB84E0AD8F5F9FCC835D6E62A9811E5EE37D542A` | `49350F6DCCBA652E8E7F052F311F94AD` |

## Metadata

- **Filename:** `TbtBusDrv_1.sys`
- **Size:** 3267320 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

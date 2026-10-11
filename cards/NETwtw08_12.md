# `NETwtw08_12.sys`

[Back to index](../README.md) · [Українська версія](NETwtw08_12.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6CB9A2EBB003CDDBFE5C3AB5D5FAEA4ED14E146440ED95CB7CFF1623B0084E74` | `4F7E9E52A0DA364AA4EFCFF2DAEB2297288EEA7A` | `0D4DB9659B93FFCDC0C6A1AC7BB256D1` |

## Metadata

- **Filename:** `NETwtw08_12.sys`
- **Size:** 8833808 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

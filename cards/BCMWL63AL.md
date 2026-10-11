# `BCMWL63AL.SYS`

[Back to index](../README.md) · [Українська версія](BCMWL63AL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `388107153B70C3107CE2DB72E319A15EF78A6BE776D155F5ECE9F9A64A3B8814` | `9AFA84F1718E4E144DC3346603898D44B7EDB532` | `34CFED0DFCC0FECF4B5F817D54904E9B` |

## Metadata

- **Filename:** `BCMWL63AL.SYS`
- **Size:** 5170176 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corporation
- **Product:** Broadcom 802.11 Network Adapter wireless driver
- **Description:** Broadcom 802.11 Network Adapter wireless driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

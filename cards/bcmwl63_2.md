# `bcmwl63_2.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9B18E146F1D8F002137C1E8A000B0A59789837DCBCDC9A28A2F262F9B5496A1D` | `2FB1A2A7562B34F7760D3482B17C6BBBA31F3060` | `55D5954B31946C2139B5F2B4D10749E1` |

## Metadata

- **Filename:** `bcmwl63_2.sys`
- **Size:** 6748336 bytes
- **Architecture:** 0x14c
- **Company:** Broadcom Corporation
- **Product:** Broadcom 802.11 Network Adapter wireless driver
- **Description:** Broadcom 802.11 Network Adapter wireless driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `NETwbw02_1.sys`

[Back to index](../README.md) · [Українська версія](NETwbw02_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD748008FF334BB40502937F20F0B30A7096361BB56DBE4A8C4DD67066D5B660` | `80EA17FBFB0FFF7C28466D02BBA625C2CB589A8E` | `57B8053A3C2A01A2C2A2DB2577D653DB` |

## Metadata

- **Filename:** `NETwbw02_1.sys`
- **Size:** 3515664 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

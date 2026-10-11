# `NETwew01_1.sys`

[Back to index](../README.md) · [Українська версія](NETwew01_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CF30F6D08AA7FC9EAA453B6273ABB92541C1C317C842F0EA690355734A68E2A6` | `48FA8E24C44301DDBFC0E5553BD4E8733B390149` | `8259EF516F176EA37BD074F42DE78C78` |

## Metadata

- **Filename:** `NETwew01_1.sys`
- **Size:** 3354384 bytes
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

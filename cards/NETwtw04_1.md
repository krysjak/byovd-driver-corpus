# `NETwtw04_1.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B91A1F2786065CF788A6C2C016A09A89B3117F4E6BC93A3E3C71868640125D50` | `186F56014EE0B9A7D0CA409213D526641A60DC0C` | `C4CAAFE8C6A996D1A5AF306AAB021F12` |

## Metadata

- **Filename:** `NETwtw04_1.sys`
- **Size:** 8654184 bytes
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

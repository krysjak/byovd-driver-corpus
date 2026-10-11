# `NETwen01.sys`

[Back to index](../README.md) · [Українська версія](NETwen01.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6BCD7E2F9AE09C75D06FF4A726C14295FB51316D921E82A08039D21406217E14` | `606AA25B7676B1B543BBEC462EB55242F1AEDAFE` | `C6A47B304C01A3B7DBD281EDF2369C5E` |

## Metadata

- **Filename:** `NETwen01.sys`
- **Size:** 2681104 bytes
- **Architecture:** 0x14c
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

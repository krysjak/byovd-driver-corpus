# `NETwen00_1.sys`

[Back to index](../README.md) · [Українська версія](NETwen00_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `96AB48F8CA7DE9120B1FB5AE9CDC5A26AEB08BF48CF3F5ADF0E6A531B81BF648` | `B1C05019F7EDAF751BA2A7A1E4BC7C9880005931` | `491F2F8CC5ED045A4F8B3D9507DCB152` |

## Metadata

- **Filename:** `NETwen00_1.sys`
- **Size:** 2677728 bytes
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

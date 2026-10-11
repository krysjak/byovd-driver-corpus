# `NETwaw16_1.sys`

[Back to index](../README.md) · [Українська версія](NETwaw16_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7DEE3ACDDA9EE11A96AE1753CEA4D7244C5EDE8FBD224E2A93D3A945646F61EA` | `B8D36B45135427FEDDA971FB51B23BD3F404EB42` | `A1B90200594C94F09F12F325D9529383` |

## Metadata

- **Filename:** `NETwaw16_1.sys`
- **Size:** 5817016 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** R Intel Wireless WiFi Link Driver
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

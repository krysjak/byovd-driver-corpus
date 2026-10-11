# `NETwsn01.sys`

[Back to index](../README.md) · [Українська версія](NETwsn01.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6051BB3DBE2B9CC4B7B38018A400FFB91ABB23C3712B0B184103A5BE4BD25772` | `0957F40D17415DCBFF6994D0EB568E1659CCE7F4` | `D98FD0EF9CF9BBD03FFBA1140E9C8E65` |

## Metadata

- **Filename:** `NETwsn01.sys`
- **Size:** 10385824 bytes
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

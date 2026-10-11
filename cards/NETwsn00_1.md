# `NETwsn00_1.sys`

[Back to index](../README.md) · [Українська версія](NETwsn00_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8B26380D3FDE8D6BD6124EBC973D378D51FD0BC5801A8BA15EB4ADDD6A6BBFED` | `04810EE59A9EC0CF67CB8B695A94F934807176FD` | `2E6EE6C80A69313F7B7100AB573A5D0C` |

## Metadata

- **Filename:** `NETwsn00_1.sys`
- **Size:** 10383264 bytes
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

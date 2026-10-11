# `NETwbn02.sys`

[Back to index](../README.md) · [Українська версія](NETwbn02.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `263F75E89766607C459BCF06C9CBBF340F8A5897FA7410D3006A86F26096AD51` | `77F38889EDE408144963A212C089911197BA6CE1` | `0FB8D7434499380EC5DB138B507645B6` |

## Metadata

- **Filename:** `NETwbn02.sys`
- **Size:** 2859288 bytes
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

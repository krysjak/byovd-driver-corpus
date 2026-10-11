# `NETwtw04_5.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C4022C6F3035BFF1E789D6AB8BC2D3A5878169D66BECD19091A1CF83BD57BD2` | `172D239C1654A0279800AA96FE3875AEE3605B2D` | `677C20DC57EA8232313BDDEBE109FAD8` |

## Metadata

- **Filename:** `NETwtw04_5.sys`
- **Size:** 8720384 bytes
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

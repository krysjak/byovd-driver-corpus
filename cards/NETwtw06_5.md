# `NETwtw06_5.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FD8276CB417D8116C21E2F5D88B7351C4BA5C433F42E31F542FA6FEDC80D594` | `D896E717AAB750AAC5DA155BAAB68BCF50ABECFF` | `8E734C73488DEB8A73FDEE1388586E62` |

## Metadata

- **Filename:** `NETwtw06_5.sys`
- **Size:** 8827168 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

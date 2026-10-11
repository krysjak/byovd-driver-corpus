# `NETwtw04_2.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DC1C03D96D593CF4520D5C24A2330820D674EC5135083D4BEBC8B0FB2DD63B2B` | `8045590DB77C4241A924F25CAD0A28A00AC97872` | `F181E801430187586BD8E1F4A6EA273A` |

## Metadata

- **Filename:** `NETwtw04_2.sys`
- **Size:** 8762936 bytes
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

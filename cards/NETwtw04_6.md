# `NETwtw04_6.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0B8CD9637BE2CAA4A178E8D6E42677DE8272AC1373FF1B857AD1BDB9F0BC5E82` | `16C817866A7C9F3E236E332C2CC5253039217CC9` | `87172ED4FE0D0D1908F31C686E036F57` |

## Metadata

- **Filename:** `NETwtw04_6.sys`
- **Size:** 7135504 bytes
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

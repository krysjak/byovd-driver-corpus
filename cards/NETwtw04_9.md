# `NETwtw04_9.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B0AC63ACBC369D4CD6B6ED61BE1A0F29255CC10657F053F895D556205F1CD9B` | `FC148F0BED2427909F813D5995E00C6F54129482` | `72ABE4AC7F43A24351E076BDE5058C02` |

## Metadata

- **Filename:** `NETwtw04_9.sys`
- **Size:** 8714872 bytes
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

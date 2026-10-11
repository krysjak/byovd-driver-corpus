# `NETwtw04_3.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9061F3EED629715595DEEE4486AA579423773794FF858DBC2C17F9B1412B2FD7` | `7201EF7CF6AC93D88D5041BD64531B64CA177315` | `2F64555DF33E8A547145FE6CF5A4D485` |

## Metadata

- **Filename:** `NETwtw04_3.sys`
- **Size:** 8776360 bytes
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

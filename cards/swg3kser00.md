# `swg3kser00.sys`

[Back to index](../README.md) · [Українська версія](swg3kser00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9CF0870E99948536D4F18D8515A385923B8B3DEB3C1F50C993DFEE289159C65C` | `D24EB4EA5659EFFB7EAD8E002AD788D8841B307E` | `ABB3DDE1953D944C20B5934166388EB7` |

## Metadata

- **Filename:** `swg3kser00.sys`
- **Size:** 287504 bytes
- **Architecture:** 0x8664
- **Company:** Sierra Wireless Incorporated
- **Product:** Sierra Wireless Incorporated USB Modem/Serial Device Driver
- **Description:** USB Modem/Serial Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

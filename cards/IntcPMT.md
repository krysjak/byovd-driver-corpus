# `IntcPMT.sys`

[Back to index](../README.md) · [Українська версія](IntcPMT.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BE24EBAA8B21B783A1BC9113F314D685759814E4F4A115493729DC623775893A` | `0403E23BD76211C79E30F619E3584B011475BAD5` | `0A923B4CC4DE148ED686488D196096A1` |

## Metadata

- **Filename:** `IntcPMT.sys`
- **Size:** 66496 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Platform Monitoring Technology Driver
- **Description:** Intel(R) Platform Monitoring Technology Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

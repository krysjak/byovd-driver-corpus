# `IntcAudioBus_8.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `948D308D91760A66B13FDF564FF04537B79F0A24E6C47CCBEF5163F2FC28ECFF` | `12C565F7EB72D7398A45358DE95D1F0A56624A90` | `221ABECBE3B4143921FF00C3768E585E` |

## Metadata

- **Filename:** `IntcAudioBus_8.sys`
- **Size:** 331760 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Smart Sound Technology BUS
- **Description:** Intel(R) Smart Sound Technology BUS
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

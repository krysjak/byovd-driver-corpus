# `swg3kser00_1.sys`

[Back to index](../README.md) · [Українська версія](swg3kser00_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `082143F0B90FA3FC3A48A3281116D10FDE9053B48B40A0BB043CB289BDD11079` | `DF19F1C1307F982A255FC78E9539DEEAAB2A6017` | `12D16A6184444EBD0F7D2633A1633C9B` |

## Metadata

- **Filename:** `swg3kser00_1.sys`
- **Size:** 251152 bytes
- **Architecture:** 0x14c
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

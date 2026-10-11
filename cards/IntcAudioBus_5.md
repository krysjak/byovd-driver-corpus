# `IntcAudioBus_5.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BEF7ACA9CD2D5BEEF750BF1D8A43BB6B594E65917B8992DD62ACABC9F75A21C` | `29669DD3C0202FE331373E549201061EED5EAB1D` | `6663819A48612F5209F15D6C90DB0E02` |

## Metadata

- **Filename:** `IntcAudioBus_5.sys`
- **Size:** 363080 bytes
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

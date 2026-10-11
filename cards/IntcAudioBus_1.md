# `IntcAudioBus_1.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B30069E639B5ECA82076E94395DE19A49210D98DC996533555C8CBB607DB1DD6` | `0D756CB8EB9E6BDC1768EBD1ECC2BF972726A1EA` | `F7AE4C6DBF9D5228DA5614E221099B3B` |

## Metadata

- **Filename:** `IntcAudioBus_1.sys`
- **Size:** 331352 bytes
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

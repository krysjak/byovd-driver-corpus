# `IntcAudioBus_7.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD21989B2F2111C0C302561ABE506A84D708B6D26220BDDD180B5D1A888B2895` | `AE0AB66704CC968AB5C504EE391B59E95ED08DE2` | `D02237B85401538965E26A5CB2FF9855` |

## Metadata

- **Filename:** `IntcAudioBus_7.sys`
- **Size:** 341456 bytes
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

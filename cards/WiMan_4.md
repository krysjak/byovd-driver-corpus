# `WiMan_4.sys`

[Back to index](../README.md) · [Українська версія](WiMan_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A6FDDFC294036629748A17A60063554323D1F22E8685132EC4DB6720493E5632` | `B56F0A4E350FF3304ABC85777AB4D03B30396ACF` | `8125694C73B64920259FFFD421AFCA8D` |

## Metadata

- **Filename:** `WiMan_4.sys`
- **Size:** 170576 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless Manageability
- **Description:** Intel® Wireless Manageability
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

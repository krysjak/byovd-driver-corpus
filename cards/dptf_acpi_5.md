# `dptf_acpi_5.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFDF94D9DD45F9E0396BC27E19A44D02A95F26E1754311CA15327ADBA95ADCFA` | `7C426E24403F007F679E164F6DA407BC87C85A2F` | `A442E9D0F9F3D3064D4C064BEEFA866C` |

## Metadata

- **Filename:** `dptf_acpi_5.sys`
- **Size:** 74584 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Dynamic Platform Thermal Framework
- **Description:** DPTF ACPI Device (64-Bit)
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

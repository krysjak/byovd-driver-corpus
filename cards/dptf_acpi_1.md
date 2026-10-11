# `dptf_acpi_1.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64D4477EAE77D690438F918105F279A74D3D88EA707E51C685042EB3B3214674` | `706619765C6D70D0107AA8B7D282907938B8C309` | `4374E77F5A87822867BABF62E31E5A77` |

## Metadata

- **Filename:** `dptf_acpi_1.sys`
- **Size:** 77224 bytes
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

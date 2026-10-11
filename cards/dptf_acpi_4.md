# `dptf_acpi_4.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0203F6844FDEC4EAA31D0F8441E2E0BE07F9B7CF55155ADDD15CF52008BDDE2B` | `7B7D4A327E63AEC6DB2438ABEFE39A1CB1AE854F` | `156225CAEDCA4722C14217CEA3EE0EF7` |

## Metadata

- **Filename:** `dptf_acpi_4.sys`
- **Size:** 78680 bytes
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

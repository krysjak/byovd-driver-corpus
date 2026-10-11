# `dptf_acpi_6.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `88AE72128DB834045ED915B84DEE22789B6A123F5E1051E6657BD53C2E9E2C56` | `E40903250FC2224D24FAC0F9AC6A71FA15F1F5F6` | `120D80CB775D1FCD02E615E3206731FE` |

## Metadata

- **Filename:** `dptf_acpi_6.sys`
- **Size:** 78832 bytes
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

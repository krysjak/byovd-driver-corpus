# `dptf_acpi_2.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9833A800C23645BAD1113D40E7B5A973721AA80E9BDDD671B3C2F210A086EB8E` | `67A12840C07322EF2C845E05A3CAFEA8DD9EE161` | `62C3DC41B595CFA91D821F64F6750580` |

## Metadata

- **Filename:** `dptf_acpi_2.sys`
- **Size:** 81056 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Dynamic Tuning
- **Description:** Intel(R) Dynamic Tuning ACPI Participant
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

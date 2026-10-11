# `ipf_acpi_1.sys`

[Back to index](../README.md) · [Українська версія](ipf_acpi_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8A85282BAC0AE0945588506B82E74EABCC8CE924E56260D74A5C1768646421F3` | `DEAC7773C60B1B2BFDCBA628BC1602F61AE3CFA8` | `B86639187D91EE5432CA58E140B95178` |

## Metadata

- **Filename:** `ipf_acpi_1.sys`
- **Size:** 85656 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Innovation Platform Framework
- **Description:** Intel(R) Innovation Platform Framework ACPI Participant
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

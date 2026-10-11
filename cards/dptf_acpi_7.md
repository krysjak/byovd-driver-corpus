# `dptf_acpi_7.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AF97AD9F6F6D711EC59AD36BA05C80B4A79E4DEEF9E9252C7781A52FFF28ED20` | `557FF091E0B00B77A710507323D1CD00220F9B64` | `F6A4005CEB6FD7E8500D871A3B158046` |

## Metadata

- **Filename:** `dptf_acpi_7.sys`
- **Size:** 77192 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Dynamic Tuning
- **Description:** Intel(R) Dynamic Tuning ACPI Participant
- **Signature:** signed
- **Source:** `oem:hp`
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

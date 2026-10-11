# `dptf_acpi.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2092109E2EE977D43E04D02176A03196DEC5293EF34DF6D76DDAC8A6AEDB8590` | `47267C7427D9FC79973AA20D0161268D8AB38EAE` | `1D3B0FACD43CE41CA5EFC3C5EA8E51F7` |

## Metadata

- **Filename:** `dptf_acpi.sys`
- **Size:** 81040 bytes
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

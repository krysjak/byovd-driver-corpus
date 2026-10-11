# `dptf_acpi_3.sys`

[Back to index](../README.md) · [Українська версія](dptf_acpi_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `406BF705E99AA2463BADD0B89F2151EB31DB66081A560E6AA0E525198AD80383` | `4330C7349E27861CEE710523EF088536DFEC266D` | `84873CD34EDAC3C2C98392EE942A695F` |

## Metadata

- **Filename:** `dptf_acpi_3.sys`
- **Size:** 76952 bytes
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

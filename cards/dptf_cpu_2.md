# `dptf_cpu_2.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `70BCA8F97027CA50E3B942367F163EA742EDD41653F7EC1B94D73A0899C33B8E` | `362C880C333739C66E176C1BE460C3CD36097A4E` | `0F040FD1B30D634B0519AF5C6118BC74` |

## Metadata

- **Filename:** `dptf_cpu_2.sys`
- **Size:** 76960 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Dynamic Tuning
- **Description:** Intel(R) Dynamic Tuning CPU Participant
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

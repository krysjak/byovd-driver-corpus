# `dptf_cpu_6.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `96BD79DD844404D0F7B5356F3F3783C5A90108BE1D22CCF50A768B6322DC347A` | `916AE0E8C246D9C4788215CA73B773F5579D0962` | `E7B48720252E0FE6712EDF6B9DD3500F` |

## Metadata

- **Filename:** `dptf_cpu_6.sys`
- **Size:** 75248 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Dynamic Platform Thermal Framework
- **Description:** DPTF CPU Device (64-Bit)
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

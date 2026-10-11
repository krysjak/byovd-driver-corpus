# `dptf_cpu_5.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E1E8CD148F3A0EB93F864A0AA8D9302A1DF5B9C2C5E4BFDF9C293D6FBF2282A0` | `46BB4C1E9812CC7FA50BA6CC52B9E14A4FF8DA50` | `A528415D99D3301B669E8933D7E45507` |

## Metadata

- **Filename:** `dptf_cpu_5.sys`
- **Size:** 69984 bytes
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

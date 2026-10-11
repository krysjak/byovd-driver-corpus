# `dptf_cpu_1.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2655F74A0F4C2575F3D57662DF52704656BFAF3E1F4FAE7443797EE70889D5AE` | `1F098862AE638D55B843988E32E71010EEBC6215` | `5F9B9A1A929E047236B4A6F637A8E7BC` |

## Metadata

- **Filename:** `dptf_cpu_1.sys`
- **Size:** 70568 bytes
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

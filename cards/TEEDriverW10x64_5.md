# `TEEDriverW10x64_5.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9E5950DFAFB611D332C331AB8B7688B55945F00D07F63154C5950625C5ED67BA` | `D6A796E80F701A13A53EDD75C431642D2FABF878` | `6384B088DDD97358109821DE76813584` |

## Metadata

- **Filename:** `TEEDriverW10x64_5.sys`
- **Size:** 318096 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
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

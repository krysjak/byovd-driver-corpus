# `TEEDriverW10_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `989AEB25857EF54F535A71D8AADBCC1547707384D93F0F01A3E076869F4FC900` | `E13D7D8BD71DF35785A4A3179ED5CA5986BDB96F` | `7FDD183367DB85FBF53B213606238816` |

## Metadata

- **Filename:** `TEEDriverW10_1.sys`
- **Size:** 272864 bytes
- **Architecture:** 0x14c
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

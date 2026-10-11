# `TEEDriverW8x64_7.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8x64_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0BAA44DEC06C5247DC901BA4633F1CB6CB9A040B62538FF03AFD6225640B3A2A` | `D30B55D9656DA26AD40A55413CAE449FFAF80555` | `08FEE1CA16B1F1EF7B1A553A7EEAC8B9` |

## Metadata

- **Filename:** `TEEDriverW8x64_7.sys`
- **Size:** 275072 bytes
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

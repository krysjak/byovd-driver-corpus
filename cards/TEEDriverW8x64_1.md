# `TEEDriverW8x64_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8x64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4846A29DD631E2E253560E7A28439AE11F244AB77F0C826AD56EA485577DBDD6` | `14F34C2F4C8B5F33A97EA1FA1FE411DBBEFA0496` | `296C443FCC228EA643ED310465772820` |

## Metadata

- **Filename:** `TEEDriverW8x64_1.sys`
- **Size:** 184608 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

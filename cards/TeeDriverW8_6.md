# `TeeDriverW8_6.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3F7E630EAAF986743A99FA38B725BD68A012D4D47EB7E187446A32FB5BD730F7` | `8DAD74412099CE0B31D6FAC2EF17F755854F69E6` | `700D18669BE2AABA61F2218707C47ED8` |

## Metadata

- **Filename:** `TeeDriverW8_6.sys`
- **Size:** 192456 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:hp`
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

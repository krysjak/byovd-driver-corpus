# `TeeDriverW8x64_4.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8x64_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4E997005F7663302F2100FECCF204D5C0E202A8328B6368C396A10DDA7FFEAF9` | `A290DF30A2D330E69728898B3D6C3AC4B3371EA4` | `A0B73E11C63EC6E194AACD606EAF01B9` |

## Metadata

- **Filename:** `TeeDriverW8x64_4.sys`
- **Size:** 266128 bytes
- **Architecture:** 0x8664
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

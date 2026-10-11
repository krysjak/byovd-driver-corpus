# `TEEDriverW8x64.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F6A771023198728E88AE1BC521668C7F806B657C79A085CFB640D72D7FDF7ADE` | `7E5668740D22DB2D252825DE986A610AAC7F3677` | `E4E18E0A78FB8E8EA5ACD608BD625C66` |

## Metadata

- **Filename:** `TEEDriverW8x64.sys`
- **Size:** 277408 bytes
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

# `TeeDriverW8_5.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `75DB74CCF5AD0155ABDE427DDB0D9A105B3AE5D2D1E3C1BEB7BA9FABF1ED1938` | `38F240C8FD1A56D5811459F1B518DF5CABBCD527` | `82CBD25441A46064294262132734A25D` |

## Metadata

- **Filename:** `TeeDriverW8_5.sys`
- **Size:** 233872 bytes
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

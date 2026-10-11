# `TeeDriverW8x64_5.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8x64_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFCB9F00A56788DD24602ABD9BA9E10F0E5D3DDD19425B8FF19DE3D1A98204CF` | `580BE09189C135C8EE620FD3C49BE516C102BBBA` | `314C3C98BC5F3B02F8427139133573C7` |

## Metadata

- **Filename:** `TeeDriverW8x64_5.sys`
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

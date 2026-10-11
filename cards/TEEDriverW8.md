# `TEEDriverW8.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A052592A8110534A4F98A970A89C98D3AE5B1B95A13EA452593457FDBD6C6F14` | `91505929AA615BD6C483CACB9F4B68EB141C1953` | `51A192A702DB46678A70C4E9162CAC07` |

## Metadata

- **Filename:** `TEEDriverW8.sys`
- **Size:** 247696 bytes
- **Architecture:** 0x14c
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

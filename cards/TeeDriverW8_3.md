# `TeeDriverW8_3.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B99689BE1615C0B81D10EDEB5FE335D716AC877F38E340987F31581D2C40F861` | `EDD008AE71D065C07E994B9062233DE0F09D231D` | `3CA4964A7446701B073A13B3C70268F7` |

## Metadata

- **Filename:** `TeeDriverW8_3.sys`
- **Size:** 178336 bytes
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

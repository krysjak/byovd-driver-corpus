# `TeeDriverW8_4.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9D217C8F93FAFEBBB911B870B37D2293311D3CC945830100C4720823ADF8A052` | `BC66E45125A158504803A804EA300417D9A2716B` | `73D3701BC83297142086385B6A4B8E26` |

## Metadata

- **Filename:** `TeeDriverW8_4.sys`
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

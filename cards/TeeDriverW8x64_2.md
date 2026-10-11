# `TeeDriverW8x64_2.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8x64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5F03180B3F892E57A9748F8987D56B20C4E445AD0DAF4BDF245D65DBC05CC832` | `184A660A1B599841BF34DFD622957A6846F7FC56` | `4A5925A9B4C511CC031B824F5275BE5E` |

## Metadata

- **Filename:** `TeeDriverW8x64_2.sys`
- **Size:** 204800 bytes
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

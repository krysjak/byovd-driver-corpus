# `TeeDriverGscW8x64_8.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverGscW8x64_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `084016B1B2361E95F0F28D72FAE6396280626FFF587BE265E8A4672CD5A12D0D` | `A25D67765266D49389F34118FCB21EB5BB6A9FC5` | `2400C6E2646B2E4311E38A34E6249E85` |

## Metadata

- **Filename:** `TeeDriverGscW8x64_8.sys`
- **Size:** 262752 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

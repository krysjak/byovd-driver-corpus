# `TEEDriverGscW8x64_7.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EF512B1E2C23A7EC77F41306D3D4D463E8554AF2F2B5D42BAF089F854CDBEA74` | `D40A6B8360A825BFF3E5493821494866E6F0AD0C` | `35D77D727D4DB96019ED3A34B466E5B2` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_7.sys`
- **Size:** 279232 bytes
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

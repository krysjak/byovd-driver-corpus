# `TeeDriverGscW8x64_9.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverGscW8x64_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `81C0E9C1DAEBF845AB530338D2CDF5C8905F25DF16873CE3C8DC5C280D12C693` | `C673684C5B8F9649131A01BEBC7A7B2EF5D88CA0` | `91B6652FFEFCAF8CDB988C3D37FE095E` |

## Metadata

- **Filename:** `TeeDriverGscW8x64_9.sys`
- **Size:** 258128 bytes
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

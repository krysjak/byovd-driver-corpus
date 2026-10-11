# `TeeDriverGscW8x64_4.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverGscW8x64_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1880CB83FF9ECA48D9026250AF75173FCE9A369E9B3048338A174339B33DD1F8` | `1F7C864420350C781CD09F4F8A2B31A4F75D7D64` | `48A5458CB6CA14AF9FBE8486F8E99C70` |

## Metadata

- **Filename:** `TeeDriverGscW8x64_4.sys`
- **Size:** 258104 bytes
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

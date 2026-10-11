# `TEEDriverGscW8x64_5.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5BD982E85DEEC1BD8D7E1D1869B3C21AA81E321DED4E7F0DD79401917DC1493D` | `AC5A5F69769C1A68F76B0168939916C17D2C3249` | `B9A2C5E17F3F6C9C07651AD2B88A0622` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_5.sys`
- **Size:** 279736 bytes
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

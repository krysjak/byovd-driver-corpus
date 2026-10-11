# `TeeDriverGscW8x64.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverGscW8x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D9652679116E277BA8A0110D4ED06B4FC380106882D914DE387557EEB726BAF2` | `994712735E1091BB06E766CE2700DDA2CEB9EFF1` | `AA16C46FC2AAA545A2EFCA92F18507E4` |

## Metadata

- **Filename:** `TeeDriverGscW8x64.sys`
- **Size:** 251152 bytes
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

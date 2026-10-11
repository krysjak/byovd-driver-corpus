# `TEEDriverGscW8x64_2.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9ED1CABC8219C2C62436D2606C633D34F75A4B820011E4EB03E3B3AF43F9E35E` | `36D96566794C2620A15E37CB3A18E62084B0DEBB` | `C8732BAB82C30A6945A4DAD8CEF67301` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_2.sys`
- **Size:** 276384 bytes
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

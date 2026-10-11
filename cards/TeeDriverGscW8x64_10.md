# `TeeDriverGscW8x64_10.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverGscW8x64_10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `960EE19FAD14586FD8054352518CD8B09B189E3206FF6AB7DA6AF6FA7EC3B8BC` | `362340483E0331836A59E13703D949D7D75058CF` | `61DC7FA1A1F1DB32AA7B7F0811ACE26E` |

## Metadata

- **Filename:** `TeeDriverGscW8x64_10.sys`
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

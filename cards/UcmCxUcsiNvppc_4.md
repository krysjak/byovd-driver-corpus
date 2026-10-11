# `UcmCxUcsiNvppc_4.sys`

[Back to index](../README.md) · [Українська версія](UcmCxUcsiNvppc_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6C56B6EA774835C65EC9F246F216EC34A3EE3BB56DF4FFA37416788FA35B8242` | `8FBE86C484B042FE7CCB48D857A856A26BC5BBBC` | `A42981D9B3D60C51AE7E27C3EDDCEAA2` |

## Metadata

- **Filename:** `UcmCxUcsiNvppc_4.sys`
- **Size:** 713328 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVPPC
- **Description:** NVIDIA PPC Function Driver.
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

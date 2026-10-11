# `UcmCxUcsiNvppc_3.sys`

[Back to index](../README.md) · [Українська версія](UcmCxUcsiNvppc_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `713A90D2C71845D7E8F080A930ED947F00AC18E6139AF81350B45418422E2C17` | `4E32B114ABD1CA53BE25A177696B10ADC12B61D1` | `73B0BCEF412F54C9C8C6480E31007981` |

## Metadata

- **Filename:** `UcmCxUcsiNvppc_3.sys`
- **Size:** 713304 bytes
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

# `amdppm_1.sys`

[Back to index](../README.md) · [Українська версія](amdppm_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8ED7A1C9E16691D3439208895CEFAE9B590B3FD8DC2C44AEF29DA358A8FBC55D` | `A22820E598D2DC10335276A58E2BA7B32DB9B5DD` | `1A13962D37AEA3A0C505E7E1D109274D` |

## Metadata

- **Filename:** `amdppm_1.sys` (Identical copies: `amdppm_3.sys`)
- **Size:** 271776 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Processor Device Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

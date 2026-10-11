# `iaStorVD_2.sys`

[Back to index](../README.md) · [Українська версія](iaStorVD_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C5DA1D9C368B757DB3E2A318CC928CF287DE32D94A1BD4F7A93058FBC18DA906` | `9F8FC3D825DDC70A52C6C481A3825CACE708E618` | `2C2232F7E03AE788A43D7940B8FEE5F0` |

## Metadata

- **Filename:** `iaStorVD_2.sys`
- **Size:** 1547464 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

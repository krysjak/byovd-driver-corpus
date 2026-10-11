# `iaStorAC_1.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `374565EDA562CD5B7057D5476C13E0EC7A01AF68DD83D16D05B012180811C5DE` | `8312AF32B4C10107FC70E81E2D873BBCA195D9DC` | `96FABF38ACC34E5AE48C8B3FFA422F62` |

## Metadata

- **Filename:** `iaStorAC_1.sys`
- **Size:** 1034200 bytes
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

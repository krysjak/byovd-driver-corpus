# `amdgpio3.sys`

[Back to index](../README.md) · [Українська версія](amdgpio3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3D5EDA5DC49154B2605201D24E70A231A72087DD78521868E5F8D3014E4B5164` | `6F8B8F54ED3E437668CEBC878D49117F55F41319` | `6E466AF1AC4443EEE7EC8DFCCAD171A6` |

## Metadata

- **Filename:** `amdgpio3.sys` (Identical copies: `amdgpio3_1.sys`, `amdgpio3_2.sys`)
- **Size:** 33592 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD GPIO Controller Driver
- **Description:** AMD GPIO Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

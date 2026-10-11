# `TbtBusDrv_2.sys`

[Back to index](../README.md) · [Українська версія](TbtBusDrv_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C348F340DC60EEC244842E44354B6FB9A1D867CB1F5B860929954140F9A38522` | `7066826B8AD9BADBAD4E4214B4987B303CCC46F5` | `87C3C457D58391E8B9967CB9DBAD3D6C` |

## Metadata

- **Filename:** `TbtBusDrv_2.sys`
- **Size:** 2991240 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

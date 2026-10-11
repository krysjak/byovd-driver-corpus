# `IntcOED_5.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `94C55B3B703D2D76F565ECBC4E29F3D64A7AF2E5520045BC689833814FA3CE87` | `09E3743E623A42808142DC1F5A224CE5751DC791` | `B3A22BE89CA48F2E4CA02D7B0209A3EC` |

## Metadata

- **Filename:** `IntcOED_5.sys`
- **Size:** 1506888 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Smart Sound Technology OED
- **Description:** Intel(R) Smart Sound Technology OED
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `dlusbaudio_1.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B144E08634AC0805CCC03C449AC21CFA3A3D69862F0065DA6421E8A0F534D0B6` | `BA7B67C2E79CABB3152288054B992953E70DFFC8` | `F21FFDD07864F70179A0DB1F1DC17D47` |

## Metadata

- **Filename:** `dlusbaudio_1.sys`
- **Size:** 177424 bytes
- **Architecture:** 0x14c
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

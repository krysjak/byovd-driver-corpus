# `dlusbaudio_2.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FF3E55E378B443F347CA972DDC597CA056041C1507172807C409DC434FB9C597` | `08ED7F089DDB2941B644BBCFCE8C1842894C0A4D` | `C91FB4A53E3A39B35747563D69C8FCBC` |

## Metadata

- **Filename:** `dlusbaudio_2.sys`
- **Size:** 168280 bytes
- **Architecture:** 0x14c
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

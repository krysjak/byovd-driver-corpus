# `atihdw83.sys`

[Back to index](../README.md) · [Українська версія](atihdw83.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FBD7E2BB1E07F3256899026FE5B7124B85051E9E215FC854DD41182D9D850961` | `4181AEEB488311666025392161B1F4E2BCB9C919` | `AFCCDF772532B2D431C363057A3757DB` |

## Metadata

- **Filename:** `atihdw83.sys`
- **Size:** 196608 bytes
- **Architecture:** 0x14c
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

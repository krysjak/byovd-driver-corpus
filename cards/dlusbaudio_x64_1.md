# `dlusbaudio_x64_1.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_x64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EF0056FE15BF636823D1046C259666FC76F402BC13D320B7F16A223B83B6D484` | `3B7F1B974D8518327B09ED623949A234149299B6` | `4D1CE9644DF69BC8E8CD36C6D6EE4708` |

## Metadata

- **Filename:** `dlusbaudio_x64_1.sys`
- **Size:** 238856 bytes
- **Architecture:** 0x8664
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

# `amdlog.sys`

[Back to index](../README.md) · [Українська версія](amdlog.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C7A5E9B652C3E8391277965EA6A2A9758174DC41233CF336E551DB5B57A263C9` | `2EDB9516DF29BADD212BC464AFAAAE48BECD8C1E` | `FF318A10EA0B1FA26359804703A62F75` |

## Metadata

- **Filename:** `amdlog.sys`
- **Size:** 106608 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD Driver
- **Description:** AMD LOG UTILITY DRIVER
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

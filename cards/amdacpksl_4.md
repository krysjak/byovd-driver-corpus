# `amdacpksl_4.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6A8CFE1C7B02C2A0DED08CA0E244581C9FF85CF93D35710DFC6763CF46337B2A` | `991DF7680A8C1A01E60DB5EBEA4B9B6C956AF55F` | `B19E0240A055059D525DB2DA93790D6C` |

## Metadata

- **Filename:** `amdacpksl_4.sys`
- **Size:** 353912 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD KSL Filter Driver
- **Description:** AMD KSL Filter Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

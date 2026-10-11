# `amdacpksl_7.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA0601CC0F248A6453D93AC8314AF5674017AE17E944E8AB3EEF8D13727E4C68` | `9F22E9BEF199BAADBD63206D6142EB4409B4FDDC` | `B7B4C1B05ABB20CB3907271E8068A575` |

## Metadata

- **Filename:** `amdacpksl_7.sys`
- **Size:** 352864 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD KSL Filter Driver
- **Description:** AMD KSL Filter Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

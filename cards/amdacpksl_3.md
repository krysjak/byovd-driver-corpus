# `amdacpksl_3.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F895362D518829FD0B209B93C2D8A44000C8D7A450232DE37DAFEAD6A760D199` | `54495B6B4B0D8B37659A442097B5F0043BA71BEC` | `8BFFFD9ECA702B2DBC5E77D4FEEC43C8` |

## Metadata

- **Filename:** `amdacpksl_3.sys`
- **Size:** 354056 bytes
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

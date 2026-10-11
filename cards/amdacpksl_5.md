# `amdacpksl_5.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D84172E7CA3228570FA9AF29E64F21D4BEFBFE37BD77DD1A9F1FFDE79F83C00C` | `FBCD50D8E3D5E4FE97D42A4923C19A927BEA0994` | `994547FF892153AF34285C0BC068444B` |

## Metadata

- **Filename:** `amdacpksl_5.sys`
- **Size:** 352880 bytes
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

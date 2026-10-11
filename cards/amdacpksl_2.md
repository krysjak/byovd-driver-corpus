# `amdacpksl_2.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1B34BAC6B83DF376A4BE3A1952456C027D6A5FA182FEFD8E817562D879126560` | `13E4877D6CD886A4E63B4A67171D78EE06228D06` | `A139F621C5BB4CFF975E87995ED30CBF` |

## Metadata

- **Filename:** `amdacpksl_2.sys`
- **Size:** 352864 bytes
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

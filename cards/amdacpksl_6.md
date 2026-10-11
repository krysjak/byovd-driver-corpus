# `amdacpksl_6.sys`

[Back to index](../README.md) · [Українська версія](amdacpksl_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `45F8EA3FE64670D8512E2A5A66C8008C5A20DD698B367311CCA6AA99ACDFEE25` | `1B1151DB2E445FC1214B947B557D1D08CF4FC989` | `A308A21E111FB57DF75A08D4423D1E19` |

## Metadata

- **Filename:** `amdacpksl_6.sys`
- **Size:** 353944 bytes
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

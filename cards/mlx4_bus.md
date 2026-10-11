# `mlx4_bus.sys`

[Back to index](../README.md) · [Українська версія](mlx4_bus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `211BDC6BB0720EE7221D77F205BD828AB4172AC4F454877BEAF5E3D74419442C` | `640189825BA80D7E2DF6F09351626CA276ACF2A0` | `1C652F46B0E067E856632651CC394863` |

## Metadata

- **Filename:** `mlx4_bus.sys` (Identical copies: `mlx4_bus_1.sys`)
- **Size:** 1132336 bytes
- **Architecture:** 0x8664
- **Company:** Mellanox
- **Product:** OpenFabrics Windows
- **Description:** MLX4 Bus Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

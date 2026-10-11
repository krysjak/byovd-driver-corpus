# `iaLPSS2_I2C_TGL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_TGL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `56A0FD540DB34782A68E7FAA3D74C5F00D8C1A1D78F9926A965501E86847F77E` | `1F7EFA826BE4AD4C561B2A8AEDB5AC5785A7F20F` | `FEBA04F32864E9E316C9312858E6546B` |

## Metadata

- **Filename:** `iaLPSS2_I2C_TGL.sys`
- **Size:** 201376 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

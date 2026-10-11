# `scsiscan.sys`

[Back to index](../README.md) · [Українська версія](scsiscan.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53EBEC1DED51573DE29E99B1B556AC759C7C2B24FE4D3D47857ADF8A723317AB` | `E43FFF9F210DD82981C2BF20D7B57D7E9AA9037B` | `5AF4C8A3F553ABA303EDA6EEC9C0BF99` |

## Metadata

- **Filename:** `scsiscan.sys`
- **Size:** 57344 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SCSI Scanner Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

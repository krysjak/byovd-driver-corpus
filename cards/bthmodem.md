# `bthmodem.sys`

[Back to index](../README.md) · [Українська версія](bthmodem.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B4DD5BDF4119C92AC27F40F40FDA788D7C722814F03573598166A2EC909DE4A4` | `DBCD814A514F2D4A45F68E6C193E20D3919A1B84` | `5FC653281F80ECEF7C92F6D641C14277` |

## Metadata

- **Filename:** `bthmodem.sys` (Identical copies: `bthmodem_1.sys`)
- **Size:** 114688 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Bluetooth Communications Driver
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

# `nvmedisk.sys`

[Back to index](../README.md) · [Українська версія](nvmedisk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ED789955358FEB3D5E7FAA3BB46E6CF69656774DBC73F61328F4071347F5724D` | `D657DFCDDC0EBC766769A3A499545B11DF2D80B1` | `6A4CD2563CDE071A97A2E3862AF62CCE` |

## Metadata

- **Filename:** `nvmedisk.sys` (Identical copies: `nvmedisk_1.sys`)
- **Size:** 128488 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Nvme Disk Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

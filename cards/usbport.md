# `usbport.sys`

[Back to index](../README.md) · [Українська версія](usbport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D18A63273C3DC26D1EA4550CC63DC59F44FD523C7CF6190FE151BE0D95D3989A` | `AAA88F3E9A94BC4E3A410352562C9416B2B93553` | `351520B1C913628D7B2297A243F00FE8` |

## Metadata

- **Filename:** `usbport.sys` (Identical copies: `usbport_1.sys`)
- **Size:** 509400 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB 1.1 & 2.0 Port Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

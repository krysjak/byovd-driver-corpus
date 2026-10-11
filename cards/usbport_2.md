# `usbport_2.sys`

[Back to index](../README.md) · [Українська версія](usbport_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5E94DFCE103E5B57A6184CA0C47848DA2EEACC7C87E15BD739D081A3A2AA7C19` | `87898F93B610A665F1F9F2DD03EC76774032B109` | `819477B95D1951FE6F4B1854CDE38813` |

## Metadata

- **Filename:** `usbport_2.sys` (Identical copies: `usbport_3.sys`)
- **Size:** 509328 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB 1.1 & 2.0 Port Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 125

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

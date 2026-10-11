# `USBSTOR.SYS`

[Back to index](../README.md) · [Українська версія](USBSTOR.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `59363B1EF2BBF72267DED60C081111D432249D2DA6EB2A21C8D238F5498ECD65` | `3080DA03FD2722A10D93A37E8DC3A0FF3B2FBCA3` | `1A943FEF92F3BABD27D68E7F9A10C6F5` |

## Metadata

- **Filename:** `USBSTOR.SYS` (Identical copies: `USBSTOR_1.SYS`)
- **Size:** 206304 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB Mass Storage Class Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

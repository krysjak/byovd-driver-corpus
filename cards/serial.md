# `serial.sys`

[Back to index](../README.md) · [Українська версія](serial.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0CCE651E05C888A994C4370233E0F68ECE99821E652CF075EA389A1B8F62515F` | `339FB97840C87F6A52F3E560CBE0DC6D630AF064` | `FC96CAFDDA51408494B3F68A21B7F05E` |

## Metadata

- **Filename:** `serial.sys` (Identical copies: `serial_1.sys`)
- **Size:** 122880 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Serial Device Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

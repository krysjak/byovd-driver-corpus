# `fdc.sys`

[Back to index](../README.md) · [Українська версія](fdc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACE9195D382EED208D1C64AE2452B8FA4D55329C5E23086D7A341C0ED19B8803` | `85D67588BB26C6E36D4958D646968D4E31A743DA` | `FF4D08D19AA23EAFFE1D594C382E5F2D` |

## Metadata

- **Filename:** `fdc.sys` (Identical copies: `fdc_1.sys`)
- **Size:** 69632 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Floppy Disk Controller Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `vmgencounter.sys`

[Back to index](../README.md) · [Українська версія](vmgencounter.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFD17E40B498AA842D59FD38E0FF128416CC6CF0AF9CB2EB7637C5E265180258` | `1586B0D36D247D38D604F377BA681F8E17B79C70` | `920813EC80D2012D5A9EF94AC35A7FEC` |

## Metadata

- **Filename:** `vmgencounter.sys` (Identical copies: `vmgencounter_1.sys`)
- **Size:** 58672 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Virtual Machine Generation Counter
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`, `system information set`

**Imports:** `MmMapIoSpaceEx`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

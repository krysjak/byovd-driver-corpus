# `pcw.sys`

[Back to index](../README.md) · [Українська версія](pcw.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B6C09B56EA59B7A63D1E77EC982A9EFA2E9F381DBEF461F490AFC0037D1C24B8` | `8E99D0A021C23C8DE7A2310E970546D9EB6C429E` | `86ADF9B97A3C7ED2A954531EEF715397` |

## Metadata

- **Filename:** `pcw.sys`
- **Size:** 103896 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Performance Counters for Windows Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `cross-process memory copy`, `process address-space attach`

**Imports:** `KeStackAttachProcess`, `MmCopyVirtualMemory`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `ahcache.sys`

[Back to index](../README.md) · [Українська версія](ahcache.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C57B690C2F0E3F1083A63B990460EE6E457F54C57C927BA7F8E09033CAD704A` | `859941DE94B034BBA550EC11D60E61AA8B35C18C` | `BEB45BB7476FA2064470146955C12862` |

## Metadata

- **Filename:** `ahcache.sys`
- **Size:** 372736 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Application Compatibility Cache
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `cross-process memory copy`, `process address-space attach`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `KeStackAttachProcess`, `MmCopyVirtualMemory`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

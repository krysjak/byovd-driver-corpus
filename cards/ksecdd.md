# `ksecdd.sys`

[Back to index](../README.md) · [Українська версія](ksecdd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA475FB8990CAA50DA5E8C53EF3FD2175FFE4EF2813341916082A66EC8118750` | `A5043B1A6EA65F27356A04963FA612795B85542A` | `9AB724A176D87551702B94FEFB2071E8` |

## Metadata

- **Filename:** `ksecdd.sys`
- **Size:** 230888 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Kernel Security Support Provider Interface
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `cross-process memory copy`

**Imports:** `MmCopyVirtualMemory`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

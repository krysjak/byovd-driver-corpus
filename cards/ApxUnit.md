# `ApxUnit.sys`

[Back to index](../README.md) · [Українська версія](ApxUnit.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64111384E06C6989F7FF8D1E1D938EC97A085493B88819C1BA4AAA6550BB44A9` | `D4E793138159CF3653B84F0A9E798D2397673E8C` | `CF2D004B6808666DA203D61674DFCE72` |

## Metadata

- **Filename:** `ApxUnit.sys`
- **Size:** 155648 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Audio Kernel-Mode Proxy Unit Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `ApxUnit_1.sys`

[Back to index](../README.md) · [Українська версія](ApxUnit_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `73435C52CAF5DEE2C42A21AE0BC8EFAE386268A19913C43511C676647BD8BEAD` | `C8D64C2340B5441920A937FFAB653B4ABC936CAB` | `39731300EEAD994AF57EB3597DF09086` |

## Metadata

- **Filename:** `ApxUnit_1.sys` (Identical copies: `ApxUnit_2.sys`)
- **Size:** 163840 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Audio Kernel-Mode Proxy Unit Driver
- **Signature:** unsigned
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 50

## Capability profile

**Primitives:** `MDL allocation`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

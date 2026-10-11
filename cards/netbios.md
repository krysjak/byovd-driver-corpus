# `netbios.sys`

[Back to index](../README.md) · [Українська версія](netbios.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `29C10B2BD9C7272C7C71462F39252A75DE0159ECCFC58BDF1C407D8C226F0AFC` | `EC099BA1625A5DC0667EA1D8AC8598B9A6D97355` | `DCB8D72D796A8F7B4173F8C378EE39EF` |

## Metadata

- **Filename:** `netbios.sys`
- **Size:** 99632 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NetBIOS interface driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

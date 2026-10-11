# `rdyboost.sys`

[Back to index](../README.md) · [Українська версія](rdyboost.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E83D146702F22E6A8FDB19B2F90ED7E745DCC3BCAE1FDC7F8AC8847A793AD2C1` | `B625D7AB187082D979CA6BC9B0D338090BCD6893` | `873694018375002888A61412CC019C1A` |

## Metadata

- **Filename:** `rdyboost.sys`
- **Size:** 316824 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** ReadyBoost Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `process address-space attach`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

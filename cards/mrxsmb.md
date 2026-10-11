# `mrxsmb.sys`

[Back to index](../README.md) · [Українська версія](mrxsmb.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A0EDBE066A3D52BF0134E7D76A757102617D1CABFEE5C0CC5E6CE9125FB0FD7A` | `F375C5E7C4D5FCF5E6E20C55E934E23DB6002422` | `C597717DE2519BD95571412A12E354DE` |

## Metadata

- **Filename:** `mrxsmb.sys`
- **Size:** 943616 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows NT SMB Minirdr
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

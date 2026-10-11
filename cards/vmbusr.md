# `vmbusr.sys`

[Back to index](../README.md) · [Українська версія](vmbusr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CA94C3A93E311E742ADBD2480212A03F6A5FF83B9BA448659EA42C32AA93DC8A` | `C3CBA4B84432C882E35814521805A5751C31AD45` | `A3B1D666C76A726325CF3CBDF5E04B2F` |

## Metadata

- **Filename:** `vmbusr.sys` (Identical copies: `vmbusr_1.sys`)
- **Size:** 316904 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Hyper-V Virtual Machine Bus Root Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

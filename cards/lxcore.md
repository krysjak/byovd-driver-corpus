# `lxcore.sys`

[Back to index](../README.md) · [Українська версія](lxcore.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CC1E56586944C7D161B3A7AB9EBEF351A72F1820291FD1565046344CC9C4ECA4` | `A7376087C7FFCA360F62FED4FB85231B92E5589D` | `94034B4728321AB227557C935D38E8EF` |

## Metadata

- **Filename:** `lxcore.sys`
- **Size:** 1127936 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** LX Core
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process termination`, `section mapping (kernel R/W surface)`, `system image loading`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmLoadSystemImage`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

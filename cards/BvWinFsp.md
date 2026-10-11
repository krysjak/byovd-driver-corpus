# `BvWinFsp.sys`

[Back to index](../README.md) · [Українська версія](BvWinFsp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C177E0EE8C16D44B79A8A87BA0431F41808D2003533F2576AB5E0633C42B900` | `89698FCFFAD8550C011097D254CF4FF962689BD6` | `F5217D7A646A91B1B07DB9BF5F072AC5` |

## Metadata

- **Filename:** `BvWinFsp.sys`
- **Size:** 168512 bytes
- **Architecture:** 0x8664
- **Company:** Navimatics LLC
- **Product:** WinFsp
- **Description:** Windows File System Proxy
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

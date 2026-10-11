# `cmgfve.sys`

[Back to index](../README.md) · [Українська версія](cmgfve.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5A8CCA31E631895A0A7AAD94F1A1819A18C2635F4861A7BEAF1C127B1F582087` | `B08F2F1B34D0924ACE53849550BCD25C1FA30E7F` | `CAD1D9716CD60F4710B7229EFF73AADE` |

## Metadata

- **Filename:** `cmgfve.sys`
- **Size:** 295520 bytes
- **Architecture:** 0x14c
- **Company:** Dell Inc.
- **Product:** CmgFVE.sys (32b,rls)
- **Description:** Credant Full Volume Encryption Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 90

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

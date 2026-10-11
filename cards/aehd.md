# `aehd.sys`

[Back to index](../README.md) · [Українська версія](aehd.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03E0F9FA171608F25C05C7DF9BC8AB717B02F037630EFA10FF53113F88AFE468` | `C50CA95DF00CF18CE868F6D895C68CD05810BE01` | `794D52BCF97AB8A78EBC7758090AB97E` |

## Metadata

- **Filename:** `aehd.sys`
- **Size:** 403080 bytes
- **Architecture:** 0x8664
- **Company:** Google LLC
- **Product:** Android Emulator hypervisor driver
- **Description:** Android Emulator hypervisor driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

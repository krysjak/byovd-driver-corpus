# `asmtxhci.sys`

[Back to index](../README.md) · [Українська версія](asmtxhci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03008CC5FB2446C08DEA0EE1BA79F34D3C933600F2B77705B5C94AAB47496355` | `CEFDDE53E7B6B9B62D21CCD6444C71F5036F8498` | `E982C13AE03192528C52FAF1B3A4ACB7` |

## Metadata

- **Filename:** `asmtxhci.sys`
- **Size:** 483504 bytes
- **Architecture:** 0x8664
- **Company:** ASMedia Technology Inc
- **Product:** ASMedia USB 3.1 Host Drivers
- **Description:** ASMedia xHCI Host Controller Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 110

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

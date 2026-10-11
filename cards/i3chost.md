# `i3chost.sys`

[Back to index](../README.md) · [Українська версія](i3chost.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `660DB171800A2848BBDFB8677911A3D2BB695F17F87D84E17BD8E85DA5501559` | `C7BB4CF27AE5A91E3D4FFF64219F495B181264EE` | `338F57B995812D19CFC571697CEE5A71` |

## Metadata

- **Filename:** `i3chost.sys`
- **Size:** 349592 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** I3C HostController Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

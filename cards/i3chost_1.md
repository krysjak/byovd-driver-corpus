# `i3chost_1.sys`

[Back to index](../README.md) · [Українська версія](i3chost_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0898003C7B9E0AD574471DCD3FD8B1BC5808088C9E5AB9875D0A93D1CBEA2A4F` | `0FDA3DFFD365C1AFD206BDF8B93361A0D01F2F5D` | `C77A68CEB92C040303398601D8A625CC` |

## Metadata

- **Filename:** `i3chost_1.sys` (Identical copies: `i3chost_2.sys`)
- **Size:** 452048 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** I3C HostController Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Live system
- **Score:** 65

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `vmx86.sys`

[Back to index](../README.md) · [Українська версія](vmx86.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4BFB88A5EBCC36A1D7C45F5B4D51BDC44BBB42179ACD023B35EE8BA87ECD9543` | `7DBB9E8284C5FD2F8EC771C84AC0422B47BD0C99` | `EF15D6C224D31A39A0D39E6C5CDCAF45` |

## Metadata

- **Filename:** `vmx86.sys`
- **Size:** 100920 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Inc.
- **Product:** VMware kernel driver
- **Description:** VMware kernel driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

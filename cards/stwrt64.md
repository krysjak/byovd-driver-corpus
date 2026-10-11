# `stwrt64.sys`

[Back to index](../README.md) · [Українська версія](stwrt64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FC4B2BD03037EC07F4443BBE13A28859035F7229CA06D4E42AFB42ABF1A89F09` | `8E0C5F83DA0C4981B31A704A73A74D00ED0DC3CC` | `71CB3BB20F08BB724769DAAAFD5AB26E` |

## Metadata

- **Filename:** `stwrt64.sys`
- **Size:** 551936 bytes
- **Architecture:** 0x8664
- **Company:** IDT, Inc.
- **Product:** IDT PC Audio
- **Description:** IDT PC Audio
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

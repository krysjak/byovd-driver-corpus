# `cht4nx64.sys`

[Back to index](../README.md) · [Українська версія](cht4nx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F03752E6E8D4E9E2B648BEA26AD2D577A13454D929AAC57F0B0E1835CD15B19` | `7DA07E996E705F3EAB5454E1F9B8D9E91D5B2EE4` | `26FA1F3228DD627CC772D7F98A066D4D` |

## Metadata

- **Filename:** `cht4nx64.sys`
- **Size:** 537904 bytes
- **Architecture:** 0x8664
- **Company:** Chelsio Communications
- **Product:** Chelsio Communications Unified Network I/O Controller
- **Description:** Chelsio Communications Unified Network I/O Controller Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

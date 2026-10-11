# `VSTBS36.SYS`

[Back to index](../README.md) · [Українська версія](VSTBS36.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `111E18952FB1F1B9D2059D8F6880FE1D5996C5D193EB8FBB2757826123739F2A` | `6957ABABBC4141A4EBD589B81AD400B996D22446` | `A42B22601CC2754428B5F82E040FD1C7` |

## Metadata

- **Filename:** `VSTBS36.SYS`
- **Size:** 287744 bytes
- **Architecture:** 0x8664
- **Company:** Conexant Systems, Inc.
- **Product:** SoftK56 Modem Driver
- **Description:** HSF_HWB3 WDM driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `bttflt.sys`

[Back to index](../README.md) · [Українська версія](bttflt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F65089C4A1B84B51D46CB758FE06AD3651EEECC72ED4A82DAD15BC419F60AD5` | `C94903347F972FC60AB2A92D6D05319BD14B9BBF` | `EBB4AC45D7A7040352CD206D0201B31C` |

## Metadata

- **Filename:** `bttflt.sys` (Identical copies: `bttflt_1.sys`)
- **Size:** 79176 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** VHD BTT Filter Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

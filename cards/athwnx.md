# `athwnx.sys`

[Back to index](../README.md) · [Українська версія](athwnx.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8047E2D20724B464B481F06C3AC1FA5734E97F7EC0D86EFEECD76480C84B3959` | `5812318223F19FA476039EC97E00EA6D46E367F0` | `D03E551165C72F2A4BBDDC566EAA819E` |

## Metadata

- **Filename:** `athwnx.sys`
- **Size:** 4233728 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Atheros Communications, Inc.
- **Product:** Driver for Qualcomm Atheros CB42/CB43/MB42/MB43 Network Adapter
- **Description:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

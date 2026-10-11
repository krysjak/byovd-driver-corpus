# `rccfg.sys`

[Back to index](../README.md) · [Українська версія](rccfg.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4531FB962055A8A6DBB5AC94928A77D42E71E0DD506D5C8BFB67381DFEF97276` | `7784ED0C4FF0135D129FFBCD37E385AC05B89154` | `B87470FAB5B027FDC3ECA22424935324` |

## Metadata

- **Filename:** `rccfg.sys`
- **Size:** 35112 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD-RAID Configuration driver
- **Description:** AMD-RAID Configuration driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

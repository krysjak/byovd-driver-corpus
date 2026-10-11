# `VSTBS26.SYS`

[Back to index](../README.md) · [Українська версія](VSTBS26.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A76C0371E9E18B038B0745C3F38AC4E958D43CB87EAB358EB88F431A33EE1F6E` | `170AC0369FE03CDD15D08AB782485180CB1005DA` | `93132C69394A99D992095D8CFE464801` |

## Metadata

- **Filename:** `VSTBS26.SYS` (Identical copies: `VSTBS26_1.SYS`)
- **Size:** 411136 bytes
- **Architecture:** 0x8664
- **Company:** Conexant Systems, Inc.
- **Product:** SoftK56 Modem Driver
- **Description:** HSF_HWB2 WDM driver
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

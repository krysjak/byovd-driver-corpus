# `iacamera64.sys`

[Back to index](../README.md) · [Українська версія](iacamera64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2262DA9DF659CB682E1F4C0FCBE9496E295858978EF4211C599A6571AEA5B3C5` | `4BA1A1159C571EA1042A654E8D4D80934DAFE271` | `131DC3C676DA77335CD98EF2579E815B` |

## Metadata

- **Filename:** `iacamera64.sys`
- **Size:** 10313376 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) AVStream Camera
- **Description:** Intel(R) AVStream Camera
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 105

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

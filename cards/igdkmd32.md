# `igdkmd32.sys`

[Back to index](../README.md) · [Українська версія](igdkmd32.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `438DF853487C52FC312717E6C051E02431843DB28E5205BA58792FC1EE7BA60B` | `5732597A65D026A63274656B854FDF943AE5E788` | `F44C39688CAD7B5A49C26154A11B2A89` |

## Metadata

- **Filename:** `igdkmd32.sys`
- **Size:** 3035568 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows 8(R)
- **Description:** Intel Graphics Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 160

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

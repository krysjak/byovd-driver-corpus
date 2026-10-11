# `igdkmd64_11.sys`

[Back to index](../README.md) · [Українська версія](igdkmd64_11.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `594D4FBF6FD2916F61F834DC862DB48CF0C3A1A3A717F3A60831556238FA9C40` | `68046B4B55BB0A78A8CA45F3D7551017076F05B3` | `608383295B37DB4AD1E02A8058108379` |

## Metadata

- **Filename:** `igdkmd64_11.sys`
- **Size:** 15499816 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 140

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

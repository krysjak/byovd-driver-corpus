# `igdkmd64_1.sys`

[Back to index](../README.md) · [Українська версія](igdkmd64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E4C8EE82C4D6D4413F6D8815C64A39052C35A7552672776AB2B3904F2940711B` | `8E5BC53B6467816DBD0BC937AB84C5953814679A` | `57E270F0A8015E342901EAC4FC8FF905` |

## Metadata

- **Filename:** `igdkmd64_1.sys`
- **Size:** 44253016 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 170

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `amdkmdag_4.sys`

[Back to index](../README.md) · [Українська версія](amdkmdag_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D4CD8F1B0CE61F69150209F44B4F119DE3E7781A6F049561787E29EC041C5F0C` | `752F60E98E97A9B103A9C13224DFA87E5E260D1D` | `DFC9FE9A0AFD33486211C74EBD13BA90` |

## Metadata

- **Filename:** `amdkmdag_4.sys`
- **Size:** 80459656 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** ATI Radeon Family
- **Description:** ATI Radeon Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 150

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

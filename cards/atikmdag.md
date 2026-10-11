# `atikmdag.sys`

[Back to index](../README.md) · [Українська версія](atikmdag.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `06DC4A7759FDA1408DEDED8CED7C18212B7E93C8EE46F77951B89B81088E7CF9` | `CF124ADE0D292ED1FB5AED24DA0C0463F387D0BF` | `F9F742807B500A10A87C69659D64C5C9` |

## Metadata

- **Filename:** `atikmdag.sys`
- **Size:** 44691312 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** ATI Radeon Family
- **Description:** ATI Radeon Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 145

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process handle access`, `process lookup`, `process termination`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

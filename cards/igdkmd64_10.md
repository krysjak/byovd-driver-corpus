# `igdkmd64_10.sys`

[Back to index](../README.md) · [Українська версія](igdkmd64_10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `19010B1862D6A898ED1052B78ACE3FB199F8CAB7E70429342154544680474629` | `BAAD21109F7B977882A76FED05D92758C2207694` | `A6F4C7AEC4B7447002C4864A261DDC79` |

## Metadata

- **Filename:** `igdkmd64_10.sys`
- **Size:** 28973640 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 140

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

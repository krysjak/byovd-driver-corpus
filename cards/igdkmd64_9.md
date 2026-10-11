# `igdkmd64_9.sys`

[Back to index](../README.md) · [Українська версія](igdkmd64_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8A4A85AFB68E8863F06AB8B26597421450A97223DA574138B00239742F6B5E26` | `9E659EDDB019AB534B192553AD3BF6E9BF282E46` | `B94D903CEC32C4AE573DB984533A81E5` |

## Metadata

- **Filename:** `igdkmd64_9.sys`
- **Size:** 28973624 bytes
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

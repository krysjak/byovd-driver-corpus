# `igdkmdn64_15.sys`

[Back to index](../README.md) · [Українська версія](igdkmdn64_15.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `20923EB4FBFE5DAAAC64A628765C86A52B4701F2BEAF3192DC59B01214D23612` | `F56EE24CBC4302C8CE1F812A5AA2847010CE6F0F` | `97B2583E28353177B79BBE12DA197DEA` |

## Metadata

- **Filename:** `igdkmdn64_15.sys`
- **Size:** 28658760 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel HD Graphics Drivers for Windows(R)
- **Description:** Intel Graphics Kernel Mode New Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 130

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

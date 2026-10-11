# `dxgkrnl.sys`

[Back to index](../README.md) · [Українська версія](dxgkrnl.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8F57DD6EFDCE62637075629C711A4D376ECBD7C77B09B0F82F5C261B3EE41358` | `D58273D48BEE7D1EFA7368F4E41C5777D7E96353` | `7325C5EF71355B40DB8137BFC2340E08` |

## Metadata

- **Filename:** `dxgkrnl.sys`
- **Size:** 5207584 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** DirectX Graphics Kernel
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `process termination`, `section mapping (kernel R/W surface)`, `section object access`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`, `ZwSetSystemInformation`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

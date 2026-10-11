# `nvlddmkm.sys`

[Back to index](../README.md) · [Українська версія](nvlddmkm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C28FD719733F0AF2E56D48EF0EF1ABE67E6FA71972D870C2F03D2D66FCC509F0` | `E3D8D4E4171D9587CA15EF33CB99D3ADE86A5BE5` | `412CB552E064341DC5F43B2772563B89` |

## Metadata

- **Filename:** `nvlddmkm.sys`
- **Size:** 120332520 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVIDIA Windows Kernel Mode Driver, Version 610.88 
- **Description:** NVIDIA Windows Kernel Mode Driver, Version 610.88 
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

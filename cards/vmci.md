# `vmci.sys`

[Back to index](../README.md) · [Українська версія](vmci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E9A45BDDB38925DED64B874644F58A6E8E87A10614ED7A34B9BDCCE6BD3D46C6` | `19FF3E6B7B988E2A14018B9B8705BE99172D6A1C` | `5B2F4B17924A5BD97EF2B7FFEC16059E` |

## Metadata

- **Filename:** `vmci.sys` (Identical copies: `vmci_1.sys`)
- **Size:** 106536 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Inc.
- **Product:** VMware PCI VMCI Bus Device
- **Description:** VMware PCI VMCI Bus Device
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

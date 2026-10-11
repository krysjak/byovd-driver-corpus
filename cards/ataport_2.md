# `ataport_2.sys`

[Back to index](../README.md) · [Українська версія](ataport_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F198A94329350CE6FFAE7D1F431799E8EC345EFE2E7C52DF8BDE9C72D2C78116` | `AB8438DB77323BCA83DD0529E4E96C6254F207A7` | `D3922D7786584FF6CD8D00A67606B558` |

## Metadata

- **Filename:** `ataport_2.sys` (Identical copies: `ataport_3.sys`)
- **Size:** 284032 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** ATAPI Driver Extension
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 140

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `CmgHiber_1.sys`

[Back to index](../README.md) · [Українська версія](CmgHiber_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8510AF9EB7759DB7F435B6F5DF9D62FCE39CA2C7CDCAEFF5CD37BE314EEEE317` | `5F7D8B9359117F0F3D1CCE63B3DAB88965D4B9DF` | `4E2345D4B374E3834FC67EBD51BF14E5` |

## Metadata

- **Filename:** `CmgHiber_1.sys`
- **Size:** 149728 bytes
- **Architecture:** 0x8664
- **Company:** Dell Inc.
- **Product:** Dell Data Protection Encryption
- **Description:** CmgHiber Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

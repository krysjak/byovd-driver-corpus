# `CmgHiber.sys`

[Back to index](../README.md) · [Українська версія](CmgHiber.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `84D106B4426F90E275EE697EAD50AB46C2FBD70F3AC0BA3D5CD443C8BCC715ED` | `2A0238D9D588A0A76D0F9A7D9963864B750BA1FA` | `257ADF8EC20D905EDB70B511E1B25D31` |

## Metadata

- **Filename:** `CmgHiber.sys`
- **Size:** 176864 bytes
- **Architecture:** 0x14c
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

# `CmgFFE.sys`

[Back to index](../README.md) · [Українська версія](CmgFFE.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `209694217C5199EA31C403B3F5E1678429DDAD4A6916F1B2275CCD28D64294F3` | `182A3704377AA3E84823AEBCD182A933120FEE7B` | `FD6BE30252F02CC333B5348DAB6A8146` |

## Metadata

- **Filename:** `CmgFFE.sys`
- **Size:** 644064 bytes
- **Architecture:** 0x14c
- **Company:** Dell Inc.
- **Product:** Dell Data Protection Encryption
- **Description:** Credant File & Folder Encryption Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

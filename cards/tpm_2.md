# `tpm_2.sys`

[Back to index](../README.md) · [Українська версія](tpm_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `35CA6FC27DBF6AD15ECCC66FE0D7E274E946FBC451E9417F6D7346B295CEBC65` | `BFC04E5E0D21AD7D31DED7E9BFF9DBBF69C5D911` | `27B5E4E372A7B68A1F47676351E7A34A` |

## Metadata

- **Filename:** `tpm_2.sys` (Identical copies: `tpm_3.sys`)
- **Size:** 374176 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** TPM Device Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 85

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

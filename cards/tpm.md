# `tpm.sys`

[Back to index](../README.md) · [Українська версія](tpm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BEF98B8653C7A2886081680CFBA5D971CE73D350517431E157929A1A83D754F` | `23718ACE2F2CC37C561D5D2503639C43DB518E65` | `19A27C8A57862B42B79A554142AC3DD0` |

## Metadata

- **Filename:** `tpm.sys` (Identical copies: `tpm_1.sys`)
- **Size:** 374224 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** TPM Device Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `pci_2.sys`

[Back to index](../README.md) · [Українська версія](pci_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B0C7874EF57637465DE089E54D2A4C2C71671F7BF34F38223A3FB6E6D637AA0` | `4871EA1C90EA4DF7A934BE8FD39062566B32BF17` | `D3FA42F3468926F54F5CCD2E64AF3A0A` |

## Metadata

- **Filename:** `pci_2.sys` (Identical copies: `pci_3.sys`)
- **Size:** 611744 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NT Plug and Play PCI Enumerator
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 90

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `pci.sys`

[Back to index](../README.md) · [Українська версія](pci.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD79656414F1354A322601B0F9B374B322B717F33A593CFD8DE2D8E28B95E4AB` | `841DBD08D8C243C51FDC8D7A8185B9C8915B9CD5` | `6CFB6774ADC69FC283A4CBC0D82595EF` |

## Metadata

- **Filename:** `pci.sys` (Identical copies: `pci_1.sys`)
- **Size:** 603632 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NT Plug and Play PCI Enumerator
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

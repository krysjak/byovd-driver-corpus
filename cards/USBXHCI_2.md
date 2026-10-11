# `USBXHCI_2.SYS`

[Back to index](../README.md) · [Українська версія](USBXHCI_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A2E321ADE62313F915CC4D5E82D44350B978A57972C2DA827A94AC0D75B91C18` | `99516E7B751DD21288991A9B8DD000B15C5352C6` | `F4587E8D460660C7C9BC97FFE3582867` |

## Metadata

- **Filename:** `USBXHCI_2.SYS` (Identical copies: `USBXHCI_3.SYS`)
- **Size:** 726400 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB XHCI Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `Usb4HostRouter.sys`

[Back to index](../README.md) · [Українська версія](Usb4HostRouter.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `89B96F603775EA22AFB955A0DA6A848B921931666C34775E6ABB0842566CC371` | `7538B5D3A23FDAF1F3446886CB9B6CB256FF55DC` | `6E31FDC711D2E58E6600FDFFF61B8A01` |

## Metadata

- **Filename:** `Usb4HostRouter.sys`
- **Size:** 714224 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB4(TM) Host Router Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `ramdisk.sys`

[Back to index](../README.md) · [Українська версія](ramdisk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E706C3C549860D3EB848D30FBD2EA9DBF5E2A96A11F050FD93F73FCA53EECFB3` | `426FA2A51C02A592E31145684D3F4BAD619F6A25` | `3EEC837D3CEBC183CF2AB5272D065B99` |

## Metadata

- **Filename:** `ramdisk.sys` (Identical copies: `ramdisk_1.sys`)
- **Size:** 75232 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** RAM Disk Driver
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

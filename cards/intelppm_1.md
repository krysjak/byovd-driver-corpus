# `intelppm_1.sys`

[Back to index](../README.md) · [Українська версія](intelppm_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37D2043835FA4A57C672B9383A0A0E73E596BBE3730BCA176BA7B15299C3C1E2` | `4D2CFAB700D2DA7C167F45C629A569B95F1BBA75` | `6458AECD43DF66C6F88D6029F7F6FF2B` |

## Metadata

- **Filename:** `intelppm_1.sys` (Identical copies: `intelppm_3.sys`)
- **Size:** 300432 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Processor Device Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

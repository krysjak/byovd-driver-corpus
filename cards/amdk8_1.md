# `amdk8_1.sys`

[Back to index](../README.md) · [Українська версія](amdk8_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F12823B0908EC5657796C38C6D3769317B68BDCFFC5D4BC6B44A729CA33E98E1` | `E2E6F92A7481905AD22CF2B9FF09797D96BF0DC4` | `A97E4A26EC88E07B6DDC900223424C63` |

## Metadata

- **Filename:** `amdk8_1.sys` (Identical copies: `amdk8_3.sys`)
- **Size:** 263552 bytes
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

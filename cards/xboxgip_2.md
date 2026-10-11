# `xboxgip_2.sys`

[Back to index](../README.md) · [Українська версія](xboxgip_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A2A28408F3E13D7C7DB4B0B4A8B2BE445FECF038F9D98F40A5B12F7FDBFCF25` | `611430989F9A2F8B3B03C70B624CBBA413D020C9` | `7D4EEFE811830A781DF5627CE175CEC2` |

## Metadata

- **Filename:** `xboxgip_2.sys` (Identical copies: `xboxgip_3.sys`)
- **Size:** 417792 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Game Input Protocol Driver
- **Signature:** unsigned
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 55

## Capability profile

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

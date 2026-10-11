# `processr_1.sys`

[Back to index](../README.md) · [Українська версія](processr_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8B536A31DDBB44EA66371703FCF4DBDA83A674996DADC58F6E122B43F385690` | `AC2EC652376D28DC9692FE4DC48D450BF6349804` | `791DA3C70652B296EBBD39234B0FF671` |

## Metadata

- **Filename:** `processr_1.sys` (Identical copies: `processr_3.sys`)
- **Size:** 271768 bytes
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

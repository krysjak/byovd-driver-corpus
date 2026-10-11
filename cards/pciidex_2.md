# `pciidex_2.sys`

[Back to index](../README.md) · [Українська версія](pciidex_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `712060C8D74BB89FA3F42E3C393897542FCBA22BDEB27466F1527D9E50905E1E` | `05E8E14ED1664DC766698604C28D8612C4DF4C39` | `2757525F9C17E13317BB4D5B2129BC0C` |

## Metadata

- **Filename:** `pciidex_2.sys` (Identical copies: `pciidex_3.sys`)
- **Size:** 91560 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** PCI IDE Bus Driver Extension
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 95

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

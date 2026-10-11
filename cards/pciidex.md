# `pciidex.sys`

[Back to index](../README.md) · [Українська версія](pciidex.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4556E5165781778FCE316704152CAFD406BA02C33C4909C51888FD6BA1C025E5` | `AC238976255CFE81613E9453AF63904111112421` | `3314DDCE20BCD33C0C3525024A3C8901` |

## Metadata

- **Filename:** `pciidex.sys` (Identical copies: `pciidex_1.sys`)
- **Size:** 91632 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** PCI IDE Bus Driver Extension
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `WiMan_5.sys`

[Back to index](../README.md) · [Українська версія](WiMan_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C15B0FB815CACFD4617B2DE68D33739F48B58EFD95338C0C530639EAA1919844` | `55B168F67B932CE57AB64430E7FB737AB06E813E` | `A8B631D98C704599C5AA3E2E6F33F689` |

## Metadata

- **Filename:** `WiMan_5.sys`
- **Size:** 170664 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless Manageability
- **Description:** Intel® Wireless Manageability
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

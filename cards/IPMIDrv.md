# `IPMIDrv.sys`

[Back to index](../README.md) · [Українська версія](IPMIDrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4399C3F5E6DB1ADA50447B3725EBA48849CE1B437BD1593B5084F165148DEFA0` | `4B81A0347ECD6CEF22E5AE8738DD58BA5C3AC68E` | `DAEAF84E2A9620BEF93254D0BBF76BD3` |

## Metadata

- **Filename:** `IPMIDrv.sys` (Identical copies: `IPMIDrv_1.sys`)
- **Size:** 169440 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** WMI IPMI DRIVER
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

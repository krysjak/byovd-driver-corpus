# `UcmCxUcsiNvppc_2.sys`

[Back to index](../README.md) · [Українська версія](UcmCxUcsiNvppc_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A386606B41C72D67C3DD6CC4FAEA0973263E850309E07E734DC4EC0A5C3BFBA4` | `135FC888C96E884E3653208BFC67209DEF7F06FE` | `445666EF082CB5223A20DBEC486072FD` |

## Metadata

- **Filename:** `UcmCxUcsiNvppc_2.sys`
- **Size:** 707816 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVPPC
- **Description:** NVIDIA PPC Function Driver.
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

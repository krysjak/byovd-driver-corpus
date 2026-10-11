# `BasicDisplay.sys`

[Back to index](../README.md) · [Українська версія](BasicDisplay.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `75AB8FD5C899616E70B6252B6C7291463F7750DE5866FBB5B6F8B0D21DAF3EEA` | `E087422737BA5AD1B0AC553DB8CF3A241CFCE42A` | `6B90CD4EAD021F3A91D7F30F23C37275` |

## Metadata

- **Filename:** `BasicDisplay.sys`
- **Size:** 106496 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Basic Display Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `driver loading`, `physical memory mapping`, `system information set`

**Imports:** `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

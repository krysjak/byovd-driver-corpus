# `IntelPMT.sys`

[Back to index](../README.md) · [Українська версія](IntelPMT.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A05600E18B156ADC34AA848FF7769C8FD90BBEF6A6F4C4DCFE5BA38D531AB584` | `C1E85BAF8E6B7FC5D1894353D971E0F6AB62B17D` | `541D08852BFE62DEE0A2BB3A94F7E83F` |

## Metadata

- **Filename:** `IntelPMT.sys` (Identical copies: `IntelPMT_1.sys`)
- **Size:** 88520 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Intel Platform Monitoring Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

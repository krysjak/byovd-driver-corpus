# `urssynopsys.sys`

[Back to index](../README.md) · [Українська версія](urssynopsys.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E41A3359DE99E673F16809BD00CC7697BB0E41C198A94DFB96D29B287B1F78E2` | `09A15FEC4341C7CBEAE190D326AF5E770A0CC297` | `505F4CA3A039CB41A02A28785D35ED06` |

## Metadata

- **Filename:** `urssynopsys.sys`
- **Size:** 66992 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** USB Role-Switch Driver for Synopsys Core
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

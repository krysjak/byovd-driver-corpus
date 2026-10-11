# `WiMan_7.sys`

[Back to index](../README.md) · [Українська версія](WiMan_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9282E6072EE1CA053D78FDC3639A7D2D8BADC60BB2426539CAC091680B89A1EB` | `33EB57DFA68FAA49F3E0C2B80ACD445E02973334` | `E3D6C44B498B9F74A799091360AB5148` |

## Metadata

- **Filename:** `WiMan_7.sys`
- **Size:** 166480 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
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

# `intelpep.sys`

[Back to index](../README.md) · [Українська версія](intelpep.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9C1E78F3AD76ADF256994D044C3F89FA960102612D1F045A6937011930FF4925` | `7F4B9B22D1B25C04B2A6B275A626D8D3F568C42A` | `C26D8ACCB6BA137B3ACCDCF58C564793` |

## Metadata

- **Filename:** `intelpep.sys` (Identical copies: `intelpep_1.sys`)
- **Size:** 657888 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Intel Power Engine Plugin
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

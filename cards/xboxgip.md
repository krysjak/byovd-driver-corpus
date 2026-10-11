# `xboxgip.sys`

[Back to index](../README.md) · [Українська версія](xboxgip.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EA57E827B3B739D89F68CB41460C3466EAC0C9D2BE128CD9F7EEA6654A816DB7` | `5D48E9362CC32CA6F37349EF8B7F4D32D815F3B6` | `32A8F55E80591EAE9D78E034DFFD13D7` |

## Metadata

- **Filename:** `xboxgip.sys` (Identical copies: `xboxgip_1.sys`)
- **Size:** 421888 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Game Input Protocol Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

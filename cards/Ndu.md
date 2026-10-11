# `Ndu.sys`

[Back to index](../README.md) · [Українська версія](Ndu.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A0B302C40FCBBE143412F99D811BAF59241EAA27271DA43100581C11B1E4C7E` | `3168C7EFE2AF3E3F3876C88923EF8BD580C49F34` | `416D3389055D85231A4B8E18686362D5` |

## Metadata

- **Filename:** `Ndu.sys`
- **Size:** 192512 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Network Data Usage Monitoring Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process lookup`

**Imports:** `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

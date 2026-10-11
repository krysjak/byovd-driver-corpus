# `rfcomm.sys`

[Back to index](../README.md) · [Українська версія](rfcomm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A5E9B12EBAAFDA10B2BE4610B5618DBFD568AF4276A1C780AA4B4B6A208CB2ED` | `84C3E0ECB1E2E9F6732015846889AD461031D17B` | `856F80DC85931317D7C454F21C0B6650` |

## Metadata

- **Filename:** `rfcomm.sys` (Identical copies: `rfcomm_1.sys`)
- **Size:** 253952 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Bluetooth RFCOMM Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

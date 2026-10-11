# `amdk8.sys`

[Back to index](../README.md) · [Українська версія](amdk8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42AF7DA6334F3227A48805B1C7AAA0A18E88353FB4B1BD4841EEC774ABB8E0FA` | `F441AB93C1FD9B77BF3596D72C03D03DAE81E845` | `C0C6D70C5241E48A4B285BBAF7532A24` |

## Metadata

- **Filename:** `amdk8.sys` (Identical copies: `amdk8_2.sys`)
- **Size:** 263680 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Processor Device Driver
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

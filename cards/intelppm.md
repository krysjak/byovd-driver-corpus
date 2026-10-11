# `intelppm.sys`

[Back to index](../README.md) · [Українська версія](intelppm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2034912ED671999583B0394B12F3AA4301A428815DE12CDFA1D33926F83B112B` | `0625795F33D4175B433D3D828EF21E89C1597002` | `73D298526484CD550D2F1857D1B04F9A` |

## Metadata

- **Filename:** `intelppm.sys` (Identical copies: `intelppm_2.sys`)
- **Size:** 300512 bytes
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

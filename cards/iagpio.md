# `iagpio.sys`

[Back to index](../README.md) · [Українська версія](iagpio.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FAAA46F22944E043A90AE6E9F0F86AF187FC2819C563DA375B2A409347BB2C35` | `2A697703D2D8913D2874614014DAE4B0F7571601` | `9E5AECAB5F05218D9AC923E7CEA1CE15` |

## Metadata

- **Filename:** `iagpio.sys` (Identical copies: `iagpio_1.sys`)
- **Size:** 36352 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Serial IO GPIO Controller Driver
- **Description:** Intel(R) Serial IO GPIO Controller Driver
- **Signature:** unsigned
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

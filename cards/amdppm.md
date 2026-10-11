# `amdppm.sys`

[Back to index](../README.md) · [Українська версія](amdppm.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BF32E3E09692993E2702F4810908AAD81283411FC4222AE65FAD28CE30C04EBE` | `9F797E6A76ED5FDC25CEE3EE45CDB983F7C7969A` | `1C48AC041B65B4EB5A64C37D1EE781B3` |

## Metadata

- **Filename:** `amdppm.sys` (Identical copies: `amdppm_2.sys`)
- **Size:** 275944 bytes
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

# `ufxsynopsys.sys`

[Back to index](../README.md) · [Українська версія](ufxsynopsys.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4B8938777B92F4F1B3199DEF96F03E710CC22D8A2720297F3F1B53A696D3347F` | `71DB31410B116C6AFD749D3AA4AE6A3277DA8946` | `186850C50025B806B391D69E916EE770` |

## Metadata

- **Filename:** `ufxsynopsys.sys` (Identical copies: `ufxsynopsys_1.sys`)
- **Size:** 198064 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** UFX Synopsys Client Driver
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

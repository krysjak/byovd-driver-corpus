# `WdNisDrv_1.sys`

[Back to index](../README.md) · [Українська версія](WdNisDrv_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36E15C5A2A0F2F28E4DDF4AAE9455F184A26CD47CA94DDE13D76E9A0BDF7D17E` | `73CC2C40A8FFDE1EA6C4C26002495DD8D06D7C2D` | `8CBE7DF54ED48B91B673A03C909C88AA` |

## Metadata

- **Filename:** `WdNisDrv_1.sys` (Identical copies: `WdNisDrv_2.sys`)
- **Size:** 102816 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Defender Network Stream Filter
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

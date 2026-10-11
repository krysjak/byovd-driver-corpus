# `WdDevFlt_1.sys`

[Back to index](../README.md) · [Українська версія](WdDevFlt_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6AC5D8D09A13DE50D96E7E49DED116E0831AB0E0A39495276A3BEEE5B45BB63B` | `76F56FA0301E28B050E9A3FC024BBE4AF84B26BC` | `A8EF466AB44B930A7CA5B70B9B5E2DEF` |

## Metadata

- **Filename:** `WdDevFlt_1.sys` (Identical copies: `WdDevFlt_2.sys`)
- **Size:** 283016 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft antimalware device filter driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Live system
- **Score:** 55

## Capability profile

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `WdDevFlt.sys`

[Back to index](../README.md) · [Українська версія](WdDevFlt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB67997A44E13DD4B6E628BD6941E956E39D9198467539C5864C92CDDACA2828` | `C83957E8D26473A6AA8F95259F1E1E5BA4056EC3` | `B6F08FE8A3756673A93AF46DE2D97B34` |

## Metadata

- **Filename:** `WdDevFlt.sys`
- **Size:** 300424 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft antimalware device filter driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

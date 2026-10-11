# `dam.sys`

[Back to index](../README.md) · [Українська версія](dam.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `256DE6D4F79F0CCA6FFFA158C6CDD97F1FE53F35A89BA73FB25B46F647E1592D` | `6AB7281F5D1873F2B48F87397A6EE7D6790B3480` | `D38F44ED72B71F923E0A8AE518260B4F` |

## Metadata

- **Filename:** `dam.sys`
- **Size:** 136664 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** DAM Kernel Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

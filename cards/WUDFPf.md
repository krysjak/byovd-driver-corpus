# `WUDFPf.sys`

[Back to index](../README.md) · [Українська версія](WUDFPf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5E46ACA0C46B2662BC3E4FD0B68C70BB4E6F00A80FD107BA731435981667FA45` | `A5E07D69772E8330E24934C3E7C118B7516E91F3` | `8018D2073EF8D4B8A1F820DC047731E4` |

## Metadata

- **Filename:** `WUDFPf.sys`
- **Size:** 173520 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Driver Foundation - User-mode Driver Framework Platform Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process address-space attach`, `process handle access`, `process termination`

**Imports:** `KeStackAttachProcess`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

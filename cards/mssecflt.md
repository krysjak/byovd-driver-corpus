# `mssecflt.sys`

[Back to index](../README.md) · [Українська версія](mssecflt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `533E27657B78A1B2DDA5A9AAD71B04D5297FE4F61F55463F6CA53B355B9C923C` | `E1005DBF33808BAD37FBC7F22C3A9D60BF35AFBB` | `5A6719636FEABA346294201526606208` |

## Metadata

- **Filename:** `mssecflt.sys`
- **Size:** 392680 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Security Events Component file system filter driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `arbitrary memory copy`, `process address-space attach`, `process lookup`

**Imports:** `KeStackAttachProcess`, `MmCopyMemory`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `spaceparser.sys`

[Back to index](../README.md) · [Українська версія](spaceparser.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C293F6A1D770CB3A564546D1D7989EED25A8BAA7B6F53CD5720CEA3562EED275` | `11331BB77FC1F8A9A702DF8452A2A138BFD79ADF` | `B0448349AAD36CAF0C6E598672B7D7E0` |

## Metadata

- **Filename:** `spaceparser.sys`
- **Size:** 86016 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storage Spaces Parser driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `volmgr.sys`

[Back to index](../README.md) · [Українська версія](volmgr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A546CBE5C7B0281545FD55672E75BDB4644313053FAED6021459BB62EF174D6D` | `7774A5ED0A1C9AA6FA975D8CDE45D561D929A0B3` | `0463124E8F5CBD9B30A57C2F98C853D2` |

## Metadata

- **Filename:** `volmgr.sys` (Identical copies: `volmgr_1.sys`)
- **Size:** 128488 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Volume Manager Driver
- **Signature:** signed
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

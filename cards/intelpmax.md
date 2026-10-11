# `intelpmax.sys`

[Back to index](../README.md) · [Українська версія](intelpmax.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AF0C3C9AE1DB6F60C65C0A046F01C740BD47E10B73FBF0A3A05BB0AB8542362B` | `DF2BEE9186B29703290E05E22F06CC1DB931371C` | `76DC389A4F660AE3688B1683A566F162` |

## Metadata

- **Filename:** `intelpmax.sys` (Identical copies: `intelpmax_1.sys`)
- **Size:** 65536 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Intel Power Limit Driver
- **Signature:** unsigned
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

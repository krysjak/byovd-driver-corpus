# `gnf.sys`

[Back to index](../README.md) · [Українська версія](gnf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A406C7CFAE7C320F58666BAB8A47D1801DD7CCFC8834A183A5E2F3905442DE9` | `9FA778C41746F1D0D10AEF7526B97C68127CC886` | `0153A075648EBCD347BA87F8649CA51A` |

## Metadata

- **Filename:** `gnf.sys`
- **Size:** 102416 bytes
- **Architecture:** 0x8664
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** GTB Extreme Network Driver
- **Description:** GTB Extreme Network Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

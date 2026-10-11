# `iorate.sys`

[Back to index](../README.md) · [Українська версія](iorate.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F35E1F621E1694495EE51306FE950739F3A83CDE80D005476D1E960303EEF53B` | `47AAA90239F39A5FAF77A168FE1D96252617D8D1` | `907123DC3C0F03F961276A3F18EA9254` |

## Metadata

- **Filename:** `iorate.sys`
- **Size:** 91624 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** I/O rate control Filter
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `hidbatt.sys`

[Back to index](../README.md) · [Українська версія](hidbatt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `23FC4EAD8368F57CF40993491F3FE7E48D2866870EEFDCE923F78BA387830E45` | `28182A470F8333BA1C96731F0D658338A7253D74` | `AD72D2B31ADD72BB9A4EB4D2C051A09C` |

## Metadata

- **Filename:** `hidbatt.sys` (Identical copies: `hidbatt_1.sys`)
- **Size:** 75168 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Hid Battery Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

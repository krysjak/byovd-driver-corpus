# `VerifierExt.sys`

[Back to index](../README.md) · [Українська версія](VerifierExt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D2FCAC287E70B20D32762728770A7BF3EA7970C1C8C1C317A7B3F93C9200542B` | `8F617EFFFA4A1E66FAB82A8B9A575283238B61EF` | `B0001C4C55DF526FF5D20B3EE442D9F2` |

## Metadata

- **Filename:** `VerifierExt.sys`
- **Size:** 271848 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Driver Verifier Extension
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

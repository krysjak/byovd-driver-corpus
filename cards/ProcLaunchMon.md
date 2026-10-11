# `ProcLaunchMon.sys`

[Back to index](../README.md) · [Українська версія](ProcLaunchMon.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3FCAC4371460EF510BEA9D772FFAD68D2AF0720078AC3BD84BD1E4979CF882E4` | `38C9C7127A50B6A360828F75A7D9815E17F84294` | `B61E3C79123E8589568111F7D9199FA7` |

## Metadata

- **Filename:** `ProcLaunchMon.sys`
- **Size:** 79880 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Time Travel Debugging Process Launch Monitor driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

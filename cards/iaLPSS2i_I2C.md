# `iaLPSS2i_I2C.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_I2C.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3F1F9EC7571D0F82D3F5BBA298965491260708F05EBAAA2CC23483521A5FF079` | `7C971D0A702EA48481C9FCA3AE127528DBEDAE20` | `149F1260537C4F68C3F67C363B62F3C5` |

## Metadata

- **Filename:** `iaLPSS2i_I2C.sys` (Identical copies: `iaLPSS2i_I2C_1.sys`)
- **Size:** 171520 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
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

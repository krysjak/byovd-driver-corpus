# `fs_rec.sys`

[Back to index](../README.md) · [Українська версія](fs_rec.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `799C95DEC78122055300086193767662A6798B537E21AB2E7B9860BE1E252EA3` | `4C258A7C69D8FC901DB308F849119519B2B18EBD` | `788BAE29776ABEBE05F1EFA3A3F7747A` |

## Metadata

- **Filename:** `fs_rec.sys`
- **Size:** 71072 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** File System Recognizer Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `driver loading`

**Imports:** `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

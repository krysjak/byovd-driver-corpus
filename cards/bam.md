# `bam.sys`

[Back to index](../README.md) · [Українська версія](bam.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9FC71FF6494CCE9A89EB224864E57371B6527227022137DA3C608B10C36EFA5D` | `9E5C5499AD2A351DFEB171FA8F520FF4A2FE900F` | `F9F24468A3001A923A2631269A49288E` |

## Metadata

- **Filename:** `bam.sys`
- **Size:** 124400 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** BAM Kernel Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process lookup`

**Imports:** `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `crashdmp.sys`

[Back to index](../README.md) · [Українська версія](crashdmp.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `25698C7ADCBB3B0413D7D58E0355D828C48FE2C8F673040F7372382AF4A6ED53` | `6D7A09C67D5E64C3F9F3DA03462E627BAF9CF69F` | `68619CFB0D944864B555A9CC52A5E217` |

## Metadata

- **Filename:** `crashdmp.sys`
- **Size:** 161272 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Crash Dump Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `system information set`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

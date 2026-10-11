# `stream.sys`

[Back to index](../README.md) · [Українська версія](stream.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C162F0DC9EECA81D13243747A35196F7F8F0DC1C316E9B88AF8A0F6CD5EEE6FA` | `1F231A3146D8BA4E181C17621F58233B4B7F7BFC` | `35F5FAEBECFE4646D966D23AB1D74052` |

## Metadata

- **Filename:** `stream.sys`
- **Size:** 118784 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** WDM CODEC Class Device Driver 2.0
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

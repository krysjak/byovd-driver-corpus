# `bowser.sys`

[Back to index](../README.md) · [Українська версія](bowser.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B30D7F70DEACDC84338EFF05212C099F412815A5FD64BB4B9EFC293C52C69C3` | `F66AD475742614DFF35560FE4D6A6CA218A6D540` | `B05E990F19C541460F3CE2BE093309AD` |

## Metadata

- **Filename:** `bowser.sys`
- **Size:** 163840 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NT Lan Manager Datagram Receiver Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

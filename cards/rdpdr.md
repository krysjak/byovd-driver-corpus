# `rdpdr.sys`

[Back to index](../README.md) · [Українська версія](rdpdr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `44176316C7F66C945D44AF6A9274DCD6C5FB9D71766B9D6B3B60F2533DD38FAD` | `8C19712BB73A7BF7768D504BBCB5672B9ECA7786` | `524B8A2152A47FBA31060262026BBEB1` |

## Metadata

- **Filename:** `rdpdr.sys`
- **Size:** 212992 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft RDP Device redirector
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `rmcast.sys`

[Back to index](../README.md) · [Українська версія](rmcast.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D8463382D7D33B129F8F428E93FFEC05721B631D5F4BA1131086ADBC16679A9` | `041EF755F0750AF7B7DC808C644EB63A343074AC` | `D69D9CB54A62D1541E5D3A67CE1E75EC` |

## Metadata

- **Filename:** `rmcast.sys`
- **Size:** 200704 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Reliable Multicast Transport
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `srvnet.sys`

[Back to index](../README.md) · [Українська версія](srvnet.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D6A74DECFD0F11FB6FFB4CACB157F6345EF5514B1DBC3B4102363F6EBCFEF9BB` | `471689E84636731AD2A18863C9F7DA33ADB5B328` | `E6C8BC3F3195298735D82BA2B083B29F` |

## Metadata

- **Filename:** `srvnet.sys`
- **Size:** 405504 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Server Network driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

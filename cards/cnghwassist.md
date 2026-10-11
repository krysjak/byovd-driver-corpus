# `cnghwassist.sys`

[Back to index](../README.md) · [Українська версія](cnghwassist.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D79879E02F6DC19F04743D78004E228D3EBF64A5CC3A57D0E0B624091BE5765` | `6165749C0EEEDEA854FF473D0477E6E5A7687A05` | `3E4D2BAEFC5BEFD32EA3923BCB96BFBF` |

## Metadata

- **Filename:** `cnghwassist.sys`
- **Size:** 75056 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** CNG Hardware Assist algorithm provider
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

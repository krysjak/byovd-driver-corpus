# `vmnetuserif.sys`

[Back to index](../README.md) · [Українська версія](vmnetuserif.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1191DD88953DBF63EE7A51182FFC019E75D78FCB13B8790644139EF9273656E4` | `A0005477CEEFEE4C833325F90006357A4B3AE8C8` | `1BF8B1EDA63954C5C6932E41FD5AA857` |

## Metadata

- **Filename:** `vmnetuserif.sys`
- **Size:** 30664 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Inc.
- **Product:** VMware network application interface driver (64-bit)
- **Description:** VMware network application interface driver (64-bit)
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

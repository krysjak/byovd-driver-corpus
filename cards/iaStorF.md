# `iaStorF.sys`

[Back to index](../README.md) · [Українська версія](iaStorF.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CB606F1A91D779324275A88FC0BFFA61E1552596BF08BB9A3455772BC867FC4F` | `CF01839D7E7E19ACEE4F48CB19C894D554191C89` | `B0EDD3C789CD3393CB1FA59657D901F2` |

## Metadata

- **Filename:** `iaStorF.sys`
- **Size:** 25448 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel Rapid Storage Technology Filter driver 
- **Description:** Intel Rapid Storage Technology Filter driver - x86
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

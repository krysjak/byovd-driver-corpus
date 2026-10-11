# `cimfs.sys`

[Back to index](../README.md) · [Українська версія](cimfs.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E8EE5DDC96E68F4A3C7C1346D289F0720F4ADB03DAC4700998A76F475A13E7` | `C8A1407A56C697AAEE3A136288D1DCFBBEABB581` | `9002CF695B573C4C28623B087C44C550` |

## Metadata

- **Filename:** `cimfs.sys`
- **Size:** 284144 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** CimFS driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

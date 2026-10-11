# `stwrt.sys`

[Back to index](../README.md) · [Українська версія](stwrt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DDFC33C46D27701025C4EF0A14ED500AAE3C42AB115BCBE36A69234AD120589C` | `D21905763B5C2710C755272392BF3C56BA091751` | `506297253A7542476EDED5EF785C92A4` |

## Metadata

- **Filename:** `stwrt.sys`
- **Size:** 459264 bytes
- **Architecture:** 0x14c
- **Company:** IDT, Inc.
- **Product:** IDT PC Audio
- **Description:** IDT PC Audio
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

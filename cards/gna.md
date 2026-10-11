# `gna.sys`

[Back to index](../README.md) · [Українська версія](gna.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ADF0A51C612499644E616AEFD8C051292C7C0405ACADB5C60D6609D05D4A5982` | `1F9FE42B907313244D32E9B9E38183140E23CC2E` | `BF631234B2C3C7543E9F1219EAFA4818` |

## Metadata

- **Filename:** `gna.sys`
- **Size:** 90304 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel (R) Gaussian & Neural Accelerator
- **Description:** Intel (R) GNA device driver (10.64.2.19041)
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** OEM package
- **Score:** 65

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

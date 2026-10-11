# `iaStorF_3.sys`

[Back to index](../README.md) · [Українська версія](iaStorF_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C0F2223CC80F23028AE6BE6784B0ACA0CCBCE289A00B0E3A5AB888055703A226` | `3EC0E7D068A4A83FFE0400DF5D32D0D662BEB7C7` | `E54EFF634E76F51FC96F32AFF33A0DD2` |

## Metadata

- **Filename:** `iaStorF_3.sys`
- **Size:** 31712 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology Filter driver 
- **Description:** Intel(R) Rapid Storage Technology Filter driver - x64
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

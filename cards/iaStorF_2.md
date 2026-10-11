# `iaStorF_2.sys`

[Back to index](../README.md) · [Українська версія](iaStorF_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0487990C54851DE824196E1E2E859C4A4E9C90896CFD97141E0445A72FC18446` | `806888DF30D7C7E4DFA56901122A296ABDEC8DF0` | `80CA8D11B20F6DE39BE00875636C3C8E` |

## Metadata

- **Filename:** `iaStorF_2.sys`
- **Size:** 28128 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology Filter driver 
- **Description:** Intel(R) Rapid Storage Technology Filter driver - x86
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

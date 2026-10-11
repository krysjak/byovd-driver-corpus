# `iaStorV.sys`

[Back to index](../README.md) · [Українська версія](iaStorV.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7E862C0367B382ADE309DEA6BEB95FD2EED15CAE8BDDA37658D66484C00F88BB` | `95DFC01672BB6667FC3AE4F9C1E349385F31B25F` | `061FA45F59C7328C4749B0E5BAA9FC52` |

## Metadata

- **Filename:** `iaStorV.sys` (Identical copies: `iaStorV_1.sys`)
- **Size:** 413088 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Matrix Storage Manager driver
- **Description:** Intel Matrix Storage Manager driver - x64
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

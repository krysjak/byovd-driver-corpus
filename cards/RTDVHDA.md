# `RTDVHDA.sys`

[Back to index](../README.md) · [Українська версія](RTDVHDA.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A5D47AF544402B3FDDF6A851805A6A630ABDAF0D3FF7F3A5D706365E0FBB3901` | `8772C5496CB1E94CD54A2DFB67ECE8A17C179FC2` | `8A2FB0F3A851CF12626A23B98EBDEAFB` |

## Metadata

- **Filename:** `RTDVHDA.sys`
- **Size:** 2004504 bytes
- **Architecture:** 0x14c
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek(r) High Definition Audio Function Driver
- **Description:** Realtek(r) High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

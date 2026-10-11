# `RTDVHDA_1.sys`

[Back to index](../README.md) · [Українська версія](RTDVHDA_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D75F2F0F836BF89E620B639798A432A4AE095DCE0282571F0F947903401BBF57` | `E15A7E236E1A9C1D367956C5C7863414EA5EA8DD` | `F9913CFCD2AABF6A03CC9C9B3D5C2C31` |

## Metadata

- **Filename:** `RTDVHDA_1.sys`
- **Size:** 1690456 bytes
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

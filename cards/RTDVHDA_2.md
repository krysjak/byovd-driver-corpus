# `RTDVHDA_2.sys`

[Back to index](../README.md) · [Українська версія](RTDVHDA_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `708551EBC475DECA8A4B0A64D4C2F7ABE70EFB3BF457B29CA206BE7FEDDB57B5` | `DD6325DF7EF9DA6E132B6341D9754CEB655184F3` | `177F3132B8B4CA6B3F021B1B3360DA7A` |

## Metadata

- **Filename:** `RTDVHDA_2.sys`
- **Size:** 1912024 bytes
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

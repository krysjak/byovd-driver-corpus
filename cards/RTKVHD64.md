# `RTKVHD64.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `60BBF11CD01CBF36450F3EACFF1DCE33368F572FB42FBD1F7002E63C73A18EA7` | `EB9D8C2D2CF7C4424B1865A4D972608EAA68A07A` | `8A6D1C881AAA19A7ECBAD1BD88ADAFE5` |

## Metadata

- **Filename:** `RTKVHD64.sys`
- **Size:** 6666192 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek(r) High Definition Audio Function Driver
- **Description:** Realtek(r) High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 110

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

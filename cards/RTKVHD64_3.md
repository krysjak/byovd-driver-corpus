# `RTKVHD64_3.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C4012C602B4556B547377F7CFA22F6DE81C3F22A0C6FFDDC9AA32C3079C6A35` | `0FE52F383A52DCA2B0A5656005CB98FAFB949AF4` | `276AF4F276DCBD0F195D3A8BA22F6E05` |

## Metadata

- **Filename:** `RTKVHD64_3.sys`
- **Size:** 6115696 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek(r) High Definition Audio Function Driver
- **Description:** Realtek(r) High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

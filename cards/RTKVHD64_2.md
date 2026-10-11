# `RTKVHD64_2.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10A65D6EC98FA2F10C4C8AFB6E45D1F59D5FE7790491E2C254B3B8C29FBB930C` | `9B8F1AF6703A904E1A1F44B897CDEB08CC852254` | `CE18D4E4D2030B625726E117262CA37A` |

## Metadata

- **Filename:** `RTKVHD64_2.sys`
- **Size:** 6333912 bytes
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

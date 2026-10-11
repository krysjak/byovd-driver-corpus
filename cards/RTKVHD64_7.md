# `RTKVHD64_7.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `77480F6EC6A2D3CEECFF2086138CA5B8C7BB3D3ABA61C8A03331ABF731EF8B16` | `47250D0B326414037BB9CCB76E9B007C00E78312` | `1525CE9413CE8084DAF6563BC2FB4940` |

## Metadata

- **Filename:** `RTKVHD64_7.sys`
- **Size:** 6185768 bytes
- **Architecture:** 0x8664
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

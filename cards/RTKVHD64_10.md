# `RTKVHD64_10.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E7A9A9086C662D8613DACEBC2AFF6DCCDCE2F1EC49D9608570E9FF2F790BEA9A` | `4ED445BDB46B72ED8C595724318EBDAF6AB03CCA` | `8CC349A13E5FA7857A92F3DDFA2AA36D` |

## Metadata

- **Filename:** `RTKVHD64_10.sys`
- **Size:** 7227992 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek(r) High Definition Audio Function Driver
- **Description:** Realtek(r) High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

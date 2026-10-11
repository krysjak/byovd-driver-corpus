# `RTKVHD64_8.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F9140EF0CF1BF84830192C83A35F6005F3AAEFDEDA33885A3368AD94081C28A9` | `D7563167C0F8A6CDB8E8EA43ED20E404B9728E47` | `AE2B99CE402CAECA06CA5D8F89EFCCAB` |

## Metadata

- **Filename:** `RTKVHD64_8.sys`
- **Size:** 5874144 bytes
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

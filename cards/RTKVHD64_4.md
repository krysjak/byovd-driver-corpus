# `RTKVHD64_4.sys`

[Back to index](../README.md) · [Українська версія](RTKVHD64_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `378A0866A1F4A5BDF20EB1A27288C28613AF8181B61378E7E54A1DB9C7F72DB5` | `B372472A99CB9043B52D4970FCB4A4B5614348C2` | `C264BA90BE1948C2DECE854A26EE95C5` |

## Metadata

- **Filename:** `RTKVHD64_4.sys`
- **Size:** 7068968 bytes
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

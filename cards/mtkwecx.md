# `mtkwecx.sys`

[Back to index](../README.md) · [Українська версія](mtkwecx.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E77858FCCF5A9698F7A5012EC641490DF75E5D8F0CE4B35062D8289FC59711C8` | `5D690C930849FE9DF8A57D331EFE6978E32A6984` | `2F99E8A1A621C7E6ED1B34F9E79C1B97` |

## Metadata

- **Filename:** `mtkwecx.sys`
- **Size:** 2524528 bytes
- **Architecture:** 0x8664
- **Company:** MediaTek Inc.
- **Product:** MediaTek Wi-Fi Adapter
- **Description:** MediaTek Wi-Fi Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

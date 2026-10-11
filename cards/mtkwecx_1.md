# `mtkwecx_1.sys`

[Back to index](../README.md) · [Українська версія](mtkwecx_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `999DAED6F8CD94C2A0AB2AE7ABAAD5001F41740B3D64583B8143D65288BCFFB8` | `FD1CD6C5669A824833BB4EB8696877006A1409B3` | `295AFA2C2BB8F1768434D1C08AD9DB47` |

## Metadata

- **Filename:** `mtkwecx_1.sys` (Identical copies: `mtkwecx_2.sys`)
- **Size:** 2369928 bytes
- **Architecture:** 0x8664
- **Company:** MediaTek Inc.
- **Product:** MediaTek Wi-Fi Adapter
- **Description:** MediaTek Wi-Fi Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

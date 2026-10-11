# `bcmpciedhd63.sys`

[Back to index](../README.md) · [Українська версія](bcmpciedhd63.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8724A7C3CECB9B1ECB597841823253ED67F6B840F5CA97B761E157808D3E2B3D` | `BC1C2CA68C9F0303AF3FF2B26548276E30FB41F9` | `796B918259C2C8BEEF0FC6ADEC3C0182` |

## Metadata

- **Filename:** `bcmpciedhd63.sys`
- **Size:** 1037824 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corp
- **Product:** Broadcom WiFi Driver wireless driver
- **Description:** Broadcom WiFi Driver wireless driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

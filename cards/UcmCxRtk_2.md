# `UcmCxRtk_2.sys`

[Back to index](../README.md) · [Українська версія](UcmCxRtk_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `47169342C1F0842CE76D4E6A36F4005490F106D8212C1DB87A1C3AEAA8EDD9AC` | `DF88BAA5216FFA6556843AA0194F358643017A38` | `800C3AC126CD405FC454CEDA08957427` |

## Metadata

- **Filename:** `UcmCxRtk_2.sys` (Identical copies: `UcmCxRtk_3.sys`)
- **Size:** 89032 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek Semiconductor Corp.
- **Description:** USB Connector Manager Realtek UCSI Client
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

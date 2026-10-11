# `UcmCxRtk.sys`

[Back to index](../README.md) · [Українська версія](UcmCxRtk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `236B7CEBAAFF464C7EE5780A9A8669BB07B473DA06A1B07904E7A54FFC054271` | `C22037874EEC3F8F752D218710E2F14DF0C47D6C` | `7677DD03C226BE9B8EA2B21F881084FE` |

## Metadata

- **Filename:** `UcmCxRtk.sys` (Identical copies: `UcmCxRtk_1.sys`)
- **Size:** 89128 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek Semiconductor Corp.
- **Description:** USB Connector Manager Realtek UCSI Client
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

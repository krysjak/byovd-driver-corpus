# `iaLPSS2_GPIO2_TGL_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_TGL_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C5B7311BA245566175E478685A152FFD12B3F6D695FA2D4EC7B3BB864287E417` | `1D19DFF5255706C516697F5C4C0BF2C9830DB158` | `22B5DF28CA7469C1C211AB7B4C6C7867` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_TGL_1.sys`
- **Size:** 131224 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

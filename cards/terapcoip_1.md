# `terapcoip_1.sys`

[Back to index](../README.md) · [Українська версія](terapcoip_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `08F25DA5DB431ECF2F3D8CAD1C3914B97B7857ED33F759773507DC60509363EE` | `ED3AF3A2554288694C4D3E3B40FC19EB8088E414` | `2B5A30C621E87DD22CCFB623812348F7` |

## Metadata

- **Filename:** `terapcoip_1.sys`
- **Size:** 113664 bytes
- **Architecture:** 0x8664
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** Windows (R) Win 7 DDK driver
- **Description:** PCoIP(R) Device
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

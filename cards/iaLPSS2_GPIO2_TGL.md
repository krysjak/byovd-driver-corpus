# `iaLPSS2_GPIO2_TGL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_TGL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `817E3D0D0543BAE67AE0252C63BAE7C81DDFEC1D93A7664FB533B95BEF38C473` | `5EA5723D1F83BAC9443AD90CFB52F939DD1E778A` | `B6D36DEA4CB1B31635354B365EC5F9AC` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_TGL.sys`
- **Size:** 128664 bytes
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

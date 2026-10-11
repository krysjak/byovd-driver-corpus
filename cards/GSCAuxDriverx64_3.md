# `GSCAuxDriverx64_3.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7FC9DD9EE124F72ACFCD299AC40A3D92B239E6C35ABDAF0F3A4D5CB78F6A71BA` | `1729C80A238E38202630DC40C35923A09DE05143` | `EA9B0CD2E96D920B38D530189ACD05F2` |

## Metadata

- **Filename:** `GSCAuxDriverx64_3.sys`
- **Size:** 102344 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Description:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

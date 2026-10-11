# `GSCAuxDriverx64_5.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A96431719F9961AA57550920A6F5AA045978BE530EA038C092EDE67A1690C7C4` | `FC6F4CA3416C4B9BC98A245F7904DB9BF8FE0DC9` | `22293D22B6A591684C139C6515775E2D` |

## Metadata

- **Filename:** `GSCAuxDriverx64_5.sys`
- **Size:** 109240 bytes
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

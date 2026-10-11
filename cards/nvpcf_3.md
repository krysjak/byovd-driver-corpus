# `nvpcf_3.sys`

[Back to index](../README.md) · [Українська версія](nvpcf_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `57A86410C5C1B2E96954D99AD86BC41BA7C29D690394F54FE2488BB7ECF22E73` | `06AC62174A791F277A7B34CD0160F3B84E3F398A` | `24FA8DB0202610E572227D707EF90B03` |

## Metadata

- **Filename:** `nvpcf_3.sys`
- **Size:** 208000 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVPCF
- **Description:** NVIDIA Platform Controllers and Framework
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 115

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

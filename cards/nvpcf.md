# `nvpcf.sys`

[Back to index](../README.md) · [Українська версія](nvpcf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `221DFB195198FB1B417A27A911CB7E17ADC8007D50546149D0C5F1CB86BF1A9A` | `A0544B59C7C5C22C29E579B6D05F73637207B37E` | `62BD8F643D2FA264C10EE2A449A1F4C3` |

## Metadata

- **Filename:** `nvpcf.sys`
- **Size:** 242816 bytes
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

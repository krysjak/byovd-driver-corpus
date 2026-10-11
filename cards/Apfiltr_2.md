# `Apfiltr_2.sys`

[Back to index](../README.md) · [Українська версія](Apfiltr_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C1C0D5DD8302AB352260999036A8CDEC9C2077702E8E95A5C124F9EFE28681F` | `6D9C31A4A7708066218023F90BB765C82E6089B5` | `42152C5D3A1719E13996307572901800` |

## Metadata

- **Filename:** `Apfiltr_2.sys`
- **Size:** 527496 bytes
- **Architecture:** 0x14c
- **Company:** Alps Electric Co., Ltd.
- **Product:** Alps Touch Pad Driver
- **Description:** Alps Touch Pad Driver
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

# `atihdwt6_4.sys`

[Back to index](../README.md) · [Українська версія](atihdwt6_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5923CCFE8B6A0829AE8E371479B5A91765A363625E7CCEF3D4FF4961001E933C` | `A64CEEA257D68A8F80B636BA3C6ADEE476AD220E` | `B0179019DF0B09AAA15D90EF75F94D60` |

## Metadata

- **Filename:** `atihdwt6_4.sys`
- **Size:** 247232 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

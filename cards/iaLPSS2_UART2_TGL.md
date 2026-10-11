# `iaLPSS2_UART2_TGL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2_TGL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FD9E0B09E4EAA3DFBD3E1112D353D5402490C15279C51084A26FF6354C54C05F` | `646EE804040623EFCD7BA789DB8269EDC317706F` | `44097DFB2277368ACBE50A927BC234BA` |

## Metadata

- **Filename:** `iaLPSS2_UART2_TGL.sys`
- **Size:** 310432 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO UART Driver
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

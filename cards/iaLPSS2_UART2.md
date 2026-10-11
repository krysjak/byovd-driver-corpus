# `iaLPSS2_UART2.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_UART2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `93462D3702DFB477475ABFBE24711B5FD4752AADE4B94A19B1F89B0094652B4B` | `0797B08AABC7505167D8D3EBEB3FF6D97F43F6F2` | `9CFB819361AE581321D47331D6765B4A` |

## Metadata

- **Filename:** `iaLPSS2_UART2.sys`
- **Size:** 307832 bytes
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

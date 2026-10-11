# `iaStorAC_6.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8E18016F08C3CB87E2C9DBFA40B1B9E9FA35ED692A172A1208F334129DFEBBAD` | `1E7C19CADD64C1EBFF31C6E906269719C5B7BF37` | `18763231FF358B20084E95F0F22EBC08` |

## Metadata

- **Filename:** `iaStorAC_6.sys`
- **Size:** 1036288 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

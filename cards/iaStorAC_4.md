# `iaStorAC_4.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1F75F0539046C81F1895F1F0364F289059402CA833A6AF734CAF8A073ADB32C8` | `3A39BCF9CA3AAD60C2E7871CEFB007B02000CCA9` | `F71B21DFAC95DCF4B8711F6CE9EA3EDD` |

## Metadata

- **Filename:** `iaStorAC_4.sys`
- **Size:** 1347776 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
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

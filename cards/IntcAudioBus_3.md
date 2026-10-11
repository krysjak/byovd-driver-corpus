# `IntcAudioBus_3.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E3D3DCF65B23E9CD4B5596EBB085C2CD9FB6B3A454DF660D322CA0802A1F8476` | `0BCC6F37629F651D0CAB317BB7612294F84695A6` | `CE010229FFDDC33BEF5E7EF2E3AEADF8` |

## Metadata

- **Filename:** `IntcAudioBus_3.sys`
- **Size:** 279928 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Description:** Intel® Smart Sound Technology (Intel® SST) Bus
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

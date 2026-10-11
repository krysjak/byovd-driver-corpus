# `TEEDriverW10x64_6.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `16E6C1F0C3146F0CF5B91CC591DD272A49E0141E6C45EC5EFB1645722EAC381B` | `483779DCDD6EF9F467FB10E8E11C04EC4A5B7912` | `08EE3F14784623C4B49FF048CB8EA000` |

## Metadata

- **Filename:** `TEEDriverW10x64_6.sys`
- **Size:** 308072 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
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

# `mtkwecx_3.sys`

[Back to index](../README.md) · [Українська версія](mtkwecx_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BB307B1EF3F674338645571163096FC2F842A6B5ED8ECB4E2123D5E5CC025F16` | `D746F417495A0A32CB54F0F7E5597F9F48895B8E` | `4CB411A92DD9F9017518A0897951719E` |

## Metadata

- **Filename:** `mtkwecx_3.sys`
- **Size:** 2181784 bytes
- **Architecture:** 0x8664
- **Company:** MediaTek Inc.
- **Product:** MediaTek Wi-Fi Adapter
- **Description:** MediaTek Wi-Fi Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

# `bcmwl63a_2.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63a_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2F23CF298A7FE8D792F7010AE8F8B21A6538D0EF272EB26BBCF0D50D4998870F` | `9391C2EFBF98DF64CF1B13FF7F0F687FA60C3B46` | `924C5566BB6849EF83C8273AB71EC692` |

## Metadata

- **Filename:** `bcmwl63a_2.sys`
- **Size:** 11762944 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corp
- **Product:** Broadcom WiFi Driver wireless driver
- **Description:** Broadcom WiFi Driver wireless driver
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

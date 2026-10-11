# `swmbbser00.sys`

[Back to index](../README.md) · [Українська версія](swmbbser00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `45869A4B5914F428C5476ED2BFACFCEE9BE78359D62CD757E4349F75A0E80D78` | `0F7539B5DDBBA1BBFEA1973E4E79CA3220333EF6` | `D3861A262D664952C9D46E899D632474` |

## Metadata

- **Filename:** `swmbbser00.sys`
- **Size:** 287816 bytes
- **Architecture:** 0x8664
- **Company:** Sierra Wireless Incorporated
- **Product:** Sierra Wireless Incorporated USB Modem/Serial Device Driver
- **Description:** USB Modem/Serial Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

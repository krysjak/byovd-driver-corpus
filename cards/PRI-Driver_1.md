# `PRI-Driver_1.sys`

[Back to index](../README.md) · [Українська версія](PRI-Driver_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36F85A96E6595F547D3C5E6E13C901BAD6E8CF559FCC63E8494CA491B2094BA2` | `AB1F6ED7D9988CAA44C6D8CB6365346C7776885F` | `FF79EEC09B74DDD8FEC59C37D8535F88` |

## Metadata

- **Filename:** `PRI-Driver_1.sys`
- **Size:** 378008 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Platform Register Interface Driver
- **Description:** Intel(R) Platform Register Interface Driver 
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

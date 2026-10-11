# `IntcAudioBus_10.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `189A880190319C5CC078AB1511256690D1E5B6C1032C29FC6739017A5EF9BCD4` | `80E0090D3488F64D0D8C4EB22D68E3FFEA41A952` | `1B83A5686B7682AA7515E038AEBA98FE` |

## Metadata

- **Filename:** `IntcAudioBus_10.sys`
- **Size:** 292936 bytes
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

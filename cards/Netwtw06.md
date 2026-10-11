# `Netwtw06.sys`

[Back to index](../README.md) · [Українська версія](Netwtw06.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D8CE74ED07FA3AABFAAAEB449A8401F9BCAD6FE93D31FC4EB11835CD978785D` | `3018E69252982935E6D9F27817D1127AEA2717BF` | `E495B2F434628B91EFDD2BAF642CC9F9` |

## Metadata

- **Filename:** `Netwtw06.sys`
- **Size:** 8803328 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

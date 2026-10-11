# `iaLPSS2_I2C.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BE868253ECEEABB5FA6F75951277014D5CD229795FA102E7BD193D2C6A853FC0` | `8C06BC3649922538CD6F7786C0FF99B7CF6661F0` | `40046515B92BCFDBC928109C7D951F3A` |

## Metadata

- **Filename:** `iaLPSS2_I2C.sys`
- **Size:** 195192 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
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

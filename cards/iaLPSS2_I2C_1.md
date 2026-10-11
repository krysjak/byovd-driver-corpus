# `iaLPSS2_I2C_1.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `513363DAB8EE96F78A7400E78A0199ACB4EB12580EEE655F60A9BCB93BD529CC` | `C92F31BD7C821D64AF5A9C1EDA998C16112A5C0E` | `35AA788A33F360F62799CB5FB313F50A` |

## Metadata

- **Filename:** `iaLPSS2_I2C_1.sys`
- **Size:** 195680 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO I2C Driver v2
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

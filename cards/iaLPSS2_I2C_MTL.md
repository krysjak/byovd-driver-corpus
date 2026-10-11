# `iaLPSS2_I2C_MTL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_MTL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5523A8FDE7F2FD820976D9075C76B28FB6354BD127FF86C47D72068B49A186C7` | `396F84F76A77FD0FF125F4078D90E6240F444897` | `3B95F016A91F6E796754A301B7851642` |

## Metadata

- **Filename:** `iaLPSS2_I2C_MTL.sys`
- **Size:** 212480 bytes
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

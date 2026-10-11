# `iaLPSS2_I2C_ICL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_ICL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACC22D47A0BE443B5562DF6B510A3DEBF01D82CD3C3606A9E18CB7B44AD7A305` | `D17133ECAACF2296231FD0750C85DAA48FD48DFE` | `471CED25B1D6BA00E4B7B6627ABF80D1` |

## Metadata

- **Filename:** `iaLPSS2_I2C_ICL.sys`
- **Size:** 200456 bytes
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

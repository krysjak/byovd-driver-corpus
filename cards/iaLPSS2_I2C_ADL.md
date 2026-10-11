# `iaLPSS2_I2C_ADL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_I2C_ADL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5EC0AE9FD89ABD8983C48EFB1E1F9323E26A10B6370D09826D50AD2725C17564` | `6BFD2236551F17708E752998EDE8940A47E2B74C` | `99EC46C839C60F9C0EEEB614B674C96F` |

## Metadata

- **Filename:** `iaLPSS2_I2C_ADL.sys`
- **Size:** 220224 bytes
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

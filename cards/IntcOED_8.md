# `IntcOED_8.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B88FE5095A68418DA9A1E13A22D47948CA8AB6267CFA86ECB41C20994B40BC65` | `14101FB311E18798DD18CAB0969993159045B1E6` | `E5EAED72095799AE2975C82CFEC15B5F` |

## Metadata

- **Filename:** `IntcOED_8.sys`
- **Size:** 1279472 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Smart Sound Technology OED
- **Description:** Intel(R) Smart Sound Technology OED
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

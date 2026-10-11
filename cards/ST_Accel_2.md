# `ST_Accel_2.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `57D6E98B766C8707C89D3220A8425CBFC08406F80D66966A55EBB1F602CD47E2` | `4ECB05D0A4926D3AF500B0A25B71A7BADF873A82` | `BD335EA8DB8DE109A32761E80B94771B` |

## Metadata

- **Filename:** `ST_Accel_2.sys`
- **Size:** 275216 bytes
- **Architecture:** 0x8664
- **Company:** STMicroelectronics
- **Product:** STM 3-Axis Accelerometer
- **Description:** STM Accelerometer Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `contiguous physical allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

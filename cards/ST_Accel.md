# `ST_Accel.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2098B2F4E012A74A5D7A9A2AA1D6DBD2E10B4DA4461F6C15881263D3508E17BB` | `7D4F0C34FBB6CC9CF14AB06AD7CFF9F488A0E5F8` | `C81FF7B2EC243657D98CAE93984D5EC9` |

## Metadata

- **Filename:** `ST_Accel.sys`
- **Size:** 75392 bytes
- **Architecture:** 0x14c
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

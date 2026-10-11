# `ST_Accel_3.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0BA077EBA6DCBB412CE3D2F6C951A025EE70AE711B881593EA1531F4CBE7EA9A` | `24A7641C0FF6F072208D6DD5F6DCA5C2EFEBC506` | `9E13A95627D802AD9F941ADBF52E2B54` |

## Metadata

- **Filename:** `ST_Accel_3.sys`
- **Size:** 115768 bytes
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

# `ST_Accel_1.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ABDC532B650FB02FB68EA1AB4165CBAC659369751EFE89F18937B1E88A793D07` | `749A32EF49C8185752CEAF97FA22D6307EF19C76` | `C6092EE49DCCB13C325A04A54A3318A6` |

## Metadata

- **Filename:** `ST_Accel_1.sys`
- **Size:** 93432 bytes
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

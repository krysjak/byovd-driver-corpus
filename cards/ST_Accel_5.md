# `ST_Accel_5.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `855E9D5B35BDF88F38AEC024AE3E6C0AE94CC4834EA8335178C7A8A0FDC20A1A` | `1537302597A926F1AC1A64A74C2C23033E7B6C57` | `DB880C094DCC4EFD0E7E45AE8C5B2F05` |

## Metadata

- **Filename:** `ST_Accel_5.sys`
- **Size:** 271928 bytes
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

# `ST_Accel_4.sys`

[Back to index](../README.md) · [Українська версія](ST_Accel_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B24D34D6076E397F688C76699B0977E9E3FC148392C3DE1077F4A5578902CD65` | `31806EF21A8EBC319EC5E41D963E366751B615D1` | `3EB4DF46F1BE48957AA96AF34D0DE6D5` |

## Metadata

- **Filename:** `ST_Accel_4.sys`
- **Size:** 137784 bytes
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

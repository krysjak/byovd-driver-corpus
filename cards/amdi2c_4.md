# `amdi2c_4.sys`

[Back to index](../README.md) · [Українська версія](amdi2c_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D12C0EF69B3C3A7284ADE336404CECAAACC7029B8CDEB1891C873EE5F919FE82` | `41336B9306B789B280CE792C10F9D865574BF83F` | `DD1B20D03F3D8B7D93EF223241895598` |

## Metadata

- **Filename:** `amdi2c_4.sys`
- **Size:** 80968 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD I2C Controller Driver
- **Description:** AMD I2C Controller Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

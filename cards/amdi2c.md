# `amdi2c.sys`

[Back to index](../README.md) · [Українська версія](amdi2c.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6EA32494A758ED615C1123D590E2BF95BBAC0C075FD913B7F8A9910441BC3B9D` | `B1580173425335AA4AF446D8AEFEA0361844F36D` | `18704304D13099948EF262501814FC41` |

## Metadata

- **Filename:** `amdi2c.sys` (Identical copies: `amdi2c_1.sys`, `amdi2c_2.sys`)
- **Size:** 84264 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD I2C Controller Driver
- **Description:** AMD I2C Controller Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11 · **Documented:** 2024-08-15
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** In the wild
- **Score:** 0 · **MITRE:** T1068

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

**Description:** 

```
sc.exe create TfSysMon.sys binPath=C:\windows\temp\TfSysMon.sys type=kernel && sc.exe start TfSysMon.sys
```

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

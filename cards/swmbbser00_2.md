# `swmbbser00_2.sys`

[Back to index](../README.md) · [Українська версія](swmbbser00_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8318DE754E108B9AF04EBF135B3CE1599419C19F65613453195FC24E8627584D` | `544C37CA26CA6F194207967DC4D70B9883B21E44` | `1E3E7F7D8DE3653A354F0590D30CF30D` |

## Metadata

- **Filename:** `swmbbser00_2.sys`
- **Size:** 288112 bytes
- **Architecture:** 0x8664
- **Company:** Sierra Wireless Incorporated
- **Product:** Sierra Wireless Incorporated USB Modem/Serial Device Driver
- **Description:** USB Modem/Serial Device Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

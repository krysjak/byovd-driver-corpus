# `iaStorAC_5.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FFE95ED5BCF8EC721B36221C4383E0D0FC698D1B8335589170B6A99CBE92A538` | `1231FBB2A76A523F9A501F0CC81992280B11476E` | `27994B3B42EDDC5BB1DB4E8BAF3FC151` |

## Metadata

- **Filename:** `iaStorAC_5.sys`
- **Size:** 1017712 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

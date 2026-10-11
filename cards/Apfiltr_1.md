# `Apfiltr_1.sys`

[Back to index](../README.md) · [Українська версія](Apfiltr_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D0973CC3C08726715B6C116E25539F79BD1960CF746ACFE668B7789EB04BF58` | `07F423D96F9A82BF915A0B66300AA58DA80CC1B5` | `0ECE1F5364EF287EAFC728880D2CA0E9` |

## Metadata

- **Filename:** `Apfiltr_1.sys`
- **Size:** 610048 bytes
- **Architecture:** 0x8664
- **Company:** Alps Electric Co., Ltd.
- **Product:** Alps Touch Pad Driver
- **Description:** Alps Touch Pad Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

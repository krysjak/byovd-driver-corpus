# `iaStorAC_3.sys`

[Back to index](../README.md) · [Українська версія](iaStorAC_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A19FAB6A0246C3FF0702331DD90B9B624953AC7143237A3D6CC8A3BB6F1EEC1B` | `F23563C4DA34A80AD416DB5B77379D9599C23042` | `2BAEBB93462A50A4348A72479553ACEB` |

## Metadata

- **Filename:** `iaStorAC_3.sys`
- **Size:** 1547496 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
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

# `iaStorA.sys`

[Back to index](../README.md) · [Українська версія](iaStorA.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `44B44A433A0B13A010C97CF0D30CF6CBF7332C6E00F33887BDF60ACB3F1887B2` | `D2F18F7DED48CB3C24956D7FF54080F4F22CB010` | `146A719B71FC6CB7AFF3585CBDD53259` |

## Metadata

- **Filename:** `iaStorA.sys`
- **Size:** 506728 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel Rapid Storage Technology driver 
- **Description:** Intel Rapid Storage Technology driver - x86
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

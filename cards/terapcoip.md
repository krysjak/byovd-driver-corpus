# `terapcoip.sys`

[Back to index](../README.md) · [Українська версія](terapcoip.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `87B899E9CA4F7C56B05B1CD3BCCE4E288D60BA611D63D60EF0FBF9E9D156A52D` | `A674A10732452307D0EA34DF40E47077E6799F76` | `91B338AF46117DD60A2FE902DAFF77B9` |

## Metadata

- **Filename:** `terapcoip.sys`
- **Size:** 97792 bytes
- **Architecture:** 0x14c
- **Company:** Windows (R) Win 7 DDK provider
- **Product:** Windows (R) Win 7 DDK driver
- **Description:** PCoIP(R) Device
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

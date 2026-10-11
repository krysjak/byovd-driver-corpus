# `amdsfhkmdf.sys`

[Back to index](../README.md) · [Українська версія](amdsfhkmdf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BBBB39686512191D3A7F785326CDDC3579F0FF2654228A6AAFCE0E05A2EF86A` | `2634D207C85E54839D1EAD38D371207FDAC854E8` | `2F63A22B5AD963ACF77587A134F5C7A6` |

## Metadata

- **Filename:** `amdsfhkmdf.sys`
- **Size:** 159936 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD SFH KMDF
- **Description:** AMD SFH KMDF
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

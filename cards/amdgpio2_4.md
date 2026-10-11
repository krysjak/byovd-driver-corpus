# `amdgpio2_4.sys`

[Back to index](../README.md) · [Українська версія](amdgpio2_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8AE3E0D6D00933D6591CDD42EFFCB4F1A8706A81768768F0CAD187BB778D5AD1` | `5BD96F22A0CE3621CB8DE85F28E42FFFEF35F64E` | `3709E9F627E5BFD231869E735F93E78B` |

## Metadata

- **Filename:** `amdgpio2_4.sys`
- **Size:** 56024 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD GPIO Controller Driver
- **Description:** AMD GPIO Controller Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

# `amdacpbus_1.sys`

[Back to index](../README.md) · [Українська версія](amdacpbus_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EC136DEECC6BE4FF1A03B7DB7EDEC2E48B4557B878FD034436C48FBD96425A67` | `3A3199D50245F40936AD6882C5BBAD8DAEDDB9C1` | `56B19F3F5E044B5EE50A8A6B673CB15F` |

## Metadata

- **Filename:** `amdacpbus_1.sys`
- **Size:** 6188472 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD Audio CoProcessor
- **Description:** AMD Audio CoProcessor
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

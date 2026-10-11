# `amdacpbus.sys`

[Back to index](../README.md) · [Українська версія](amdacpbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `915F7B818BBEB3F0B879AFF30C62EB981641B1616B63F0A629FF87E79757287C` | `F650058A3FACEDF4DFCAFB72EA7CD72852394D25` | `6E7715E96AA5C573CDACC8F1B1117E3D` |

## Metadata

- **Filename:** `amdacpbus.sys`
- **Size:** 1386912 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD Audio CoProcessor
- **Description:** AMD Audio CoProcessor
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

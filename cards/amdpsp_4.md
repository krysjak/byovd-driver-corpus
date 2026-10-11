# `amdpsp_4.sys`

[Back to index](../README.md) · [Українська версія](amdpsp_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA09BAF79AE92424ABC96E42D1F30DD0A60DA62CB9091BD4BC74F36AEEDF932F` | `2CB17A5A474C66F5CE2A68D7C03CF7399874D86E` | `8954D35CAF3A6E37C6DE8F90A883E288` |

## Metadata

- **Filename:** `amdpsp_4.sys`
- **Size:** 52656 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc. 
- **Product:** Advanced Micro Devices, Inc. amdpsp sys
- **Description:** amdpsp sys
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

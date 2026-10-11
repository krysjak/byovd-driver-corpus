# `amdpmf.sys`

[Back to index](../README.md) · [Українська версія](amdpmf.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3B877B4AB3862A4D700605043501EC04E1A5CDA3595156F4C3BF36815E9FB04C` | `17CB4DE82A365B704D0FF6553A43FE3ED56CC4AA` | `926AF88B5FCF8DE8BD56BEBBC1B77FA8` |

## Metadata

- **Filename:** `amdpmf.sys`
- **Size:** 202136 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc.
- **Product:** AMD PMF Device Driver
- **Description:** AMD PMF Driver
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

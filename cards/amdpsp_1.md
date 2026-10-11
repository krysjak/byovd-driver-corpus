# `amdpsp_1.sys`

[Back to index](../README.md) · [Українська версія](amdpsp_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `353AB70AE1E174A5E9B908B1F73B5D9760CAD5F6A24EBC0CF60C18723BD314FF` | `065FFDD7244BA2C062CD457DC3DEFB7D313C5FBE` | `EDDE442DCE6DC0BEC4721365D6ACBC9C` |

## Metadata

- **Filename:** `amdpsp_1.sys` (Identical copies: `amdpsp_3.sys`)
- **Size:** 60224 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc. 
- **Product:** Advanced Micro Devices, Inc. amdpsp sys
- **Description:** amdpsp sys
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

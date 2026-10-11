# `AtihdWT6.sys`

[Back to index](../README.md) · [Українська версія](AtihdWT6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA04C1DEDDC62380548A34681A320DF644EBA0C387576953B50C7A05CD8CA012` | `3F2FC6CDCF9AFE7B4329354259C4F891A6D08910` | `50DC0AA74FBA44D93F8B5B7C96E90FCA` |

## Metadata

- **Filename:** `AtihdWT6.sys`
- **Size:** 255304 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

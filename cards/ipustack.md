# `ipustack.sys`

[Back to index](../README.md) · [Українська версія](ipustack.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C4A7AB4F7F6838961E15C42F2BF7258E0939C3D2F8EC1CA011127C6B3396EBFC` | `D6B486B2EF667B4F4F6E786FBF0F972C5DF5D6E5` | `E7F13642B653AEFD319EEB6ACB132467` |

## Metadata

- **Filename:** `ipustack.sys`
- **Size:** 372032 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD IPU Driver
- **Description:** AMD IPU Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `driver loading`, `physical address resolution`

**Imports:** `MmGetPhysicalAddress`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

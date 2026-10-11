# `IshOed.sys`

[Back to index](../README.md) · [Українська версія](IshOed.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FE4BB14246D87E2177274F126AD9AD877F6879011301EA97CD258CB5075AC375` | `509E8AC67C61A3749FB4CD6915AD9D83B3A8BB92` | `2D9D3694DFE1A9C76F8C2603EE19D2DD` |

## Metadata

- **Filename:** `IshOed.sys`
- **Size:** 73808 bytes
- **Architecture:** 0x8664
- **Company:** Intel
- **Product:** ISS
- **Description:** Intel(R) Integrated Sensor Solution
- **Signature:** signed
- **Source:** `oem:dell`
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

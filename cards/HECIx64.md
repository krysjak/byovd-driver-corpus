# `HECIx64.sys`

[Back to index](../README.md) · [Українська версія](HECIx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D69F522EEE764AAFA4BB1520778BFA59F3DFEB87453F76672BF9B605E5B5C711` | `4BE472294B90B4EB8E8D7751E8D43C3E19E5622D` | `F1A67CF6EA9DD11BFC730AB990C67D97` |

## Metadata

- **Filename:** `HECIx64.sys`
- **Size:** 64472 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

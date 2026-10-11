# `TEEDriverGscW8x64_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F45AF79006486102343130CFC6A1C0EF441942F1ABC85C591E25FE62302F847B` | `6ADC7B88672C5B0871BF0255F5DEABD9C71AC431` | `0A45ECC24C27EBDFED12EAB0B95E6A5D` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_1.sys`
- **Size:** 259824 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
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

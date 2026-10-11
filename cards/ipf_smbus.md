# `ipf_smbus.sys`

[Back to index](../README.md) · [Українська версія](ipf_smbus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `672EB5C1D67AD52586713AC80131CDF6C21DA5CB3EE9CB211AE14FAEB8F8EE83` | `38A38F8F0E1AA9AF7BCD88BAED788989422AB39A` | `F5D24E39FC4064431229EF03B6E2B572` |

## Metadata

- **Filename:** `ipf_smbus.sys`
- **Size:** 73288 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Innovation Platform Framework
- **Description:** Intel(R) Innovation Platform Framework SMBUS Driver
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

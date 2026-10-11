# `NETwtw06_6.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D9576367DE1E82AD9FB81C8E3DF6E34497320B4ED3D41F4D8AD8D99BC6C4458A` | `4A3F73454147EBA44231DEE0F5FE3D7DB844656B` | `3EFF7B459E1C7275CC4853C7BEB12098` |

## Metadata

- **Filename:** `NETwtw06_6.sys`
- **Size:** 8832792 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

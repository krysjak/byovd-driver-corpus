# `NETwaw10.sys`

[Back to index](../README.md) · [Українська версія](NETwaw10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0B89F692E74C15585D3E3582A3B1A2064D9597EBBDE8D91B156E20650CA672A2` | `37A835F5D3F8066E125EFF25F58E4026C7707F07` | `F138CB339CEEE2EB456845D2DC07288F` |

## Metadata

- **Filename:** `NETwaw10.sys`
- **Size:** 5178424 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
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

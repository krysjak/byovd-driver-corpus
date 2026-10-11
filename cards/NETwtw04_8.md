# `NETwtw04_8.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2676C4361E1CF01502F29842EF2761B36E92E9EDA93A0E369733DC21C7C3E1F8` | `B42DE6662B2BD8E772DD2599C609CC98C18DBE13` | `18E5C382E3EBB25C87452F5A2DFF2F62` |

## Metadata

- **Filename:** `NETwtw04_8.sys`
- **Size:** 8673040 bytes
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

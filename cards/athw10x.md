# `athw10x.sys`

[Back to index](../README.md) · [Українська версія](athw10x.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7C65FE533B4A93CA3621032A49260320E190684EE797A69B90B5C4C457CA457E` | `F51F884301F263B60350C98F9D71BB4F8EA323EA` | `2557EF2B68CB9AC8E06D9EE54450DE1A` |

## Metadata

- **Filename:** `athw10x.sys`
- **Size:** 4317112 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Atheros Communications, Inc.
- **Product:** Driver for Qualcomm Atheros CB42/CB43/MB42/MB43 Network Adapter
- **Description:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 105

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

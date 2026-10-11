# `AMDPCIDev.sys`

[Back to index](../README.md) · [Українська версія](AMDPCIDev.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `48FDADD0651BE4D5081CC636C0CCDA30C602506F4C02ED58D9A3E46B74C4564D` | `2D0B685A5F6B46E74499DB29D3D5F56144220C39` | `F5B4FC4DBF511C6DB3EAAC710421EB4C` |

## Metadata

- **Filename:** `AMDPCIDev.sys`
- **Size:** 39048 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD PCI Device driver
- **Description:** AMD PCI Device driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

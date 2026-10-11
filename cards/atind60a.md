# `atind60a.sys`

[Back to index](../README.md) · [Українська версія](atind60a.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CEB38E216A6E6263CE1AD9A61B5715F2F59555DCCD4DC15103B6012E00F8A991` | `CEB443ADB2175BDD9551CC3AD9979516C9266377` | `267DFE5D6577A7D148B3C46C4CAB659E` |

## Metadata

- **Filename:** `atind60a.sys`
- **Size:** 544360 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Limited
- **Product:** Broadcom NetXtreme Gigabit Ethernet Driver
- **Description:** Broadcom NetXtreme Gigabit Ethernet NDIS6.x Unified Driver.
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 115

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

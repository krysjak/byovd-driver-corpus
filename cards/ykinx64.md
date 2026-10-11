# `ykinx64.sys`

[Back to index](../README.md) · [Українська версія](ykinx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `823EE97F1EAFA80E3D3692EC5CD79E8F0C7AD8222AC96DA009EBE9F709555BF8` | `DC97D8F78F787A54FC70FCE80612F1854B6DC362` | `E9C0D4DFF1F4E0F4B4534114E2185DCD` |

## Metadata

- **Filename:** `ykinx64.sys`
- **Size:** 288768 bytes
- **Architecture:** 0x8664
- **Company:** Marvell
- **Product:** Marvell Yukon Ethernet Controller
- **Description:** NDIS6.30 Miniport Driver for Marvell Yukon Ethernet Controller
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `iaLPSS2_GPIO2_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_GPIO2_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03B7F1F6BF593BB804A3604230002EBDB679C7A11BF2F7F34388D3F16CB2FF7E` | `53BA394294308F285E4C5D34DB34E297139BF283` | `75FB2412D54AB939A349917905BB2A2E` |

## Metadata

- **Filename:** `iaLPSS2_GPIO2_CNL.sys`
- **Size:** 128776 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

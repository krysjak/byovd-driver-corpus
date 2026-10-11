# `WiMan_3.sys`

[Back to index](../README.md) · [Українська версія](WiMan_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2C291AC5786A136AF0CBA172B29F8C72EFEBA9382717B9B710FD19B01E6CE6DB` | `291B2D86605D1B8213F518B013921ADED8DA30E6` | `9F1A79AFBD1F528C5DF1347449B3EDC3` |

## Metadata

- **Filename:** `WiMan_3.sys`
- **Size:** 167992 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless Manageability
- **Description:** Intel® Wireless Manageability
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

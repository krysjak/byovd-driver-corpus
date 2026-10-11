# `FTDIBUS.sys`

[Back to index](../README.md) · [Українська версія](FTDIBUS.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D7C7571FC89D448E8D27FDD0AA0BAF1DFE38291581FE80D09369C217470C0E94` | `1AFF26B7281CC40B321D0B60A7A06278E6A73CC7` | `2B1F0E118D1BD6D40A2974D5700BD305` |

## Metadata

- **Filename:** `FTDIBUS.sys`
- **Size:** 148128 bytes
- **Architecture:** 0x8664
- **Company:** FTDI Ltd.
- **Product:** FTDIChip CDM Universal Drivers
- **Description:** FTDIBUS USB Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 50

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

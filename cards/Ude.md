# `Ude.sys`

[Back to index](../README.md) · [Українська версія](Ude.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `80009C87CB69B489F0CDB5997100DACAADF2A172907892F68067DCF0FC11F51C` | `8CCDEA39CF91CB8882EC8A565D3C63A48E212330` | `3B44A218EBADD4BD5FEE9D2529ADAF0A` |

## Metadata

- **Filename:** `Ude.sys`
- **Size:** 337384 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Telephony Stack
- **Description:** UDE Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

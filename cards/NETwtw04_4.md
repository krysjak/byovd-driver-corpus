# `NETwtw04_4.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B6E3457853FE2253CB4FAB6DC9BC44684A264185169B4E295057C41ACB455C3` | `66CE7751F6146D7FFD2AD52B10843621758695BD` | `820E245D7A648B0AE32152213AFFF14C` |

## Metadata

- **Filename:** `NETwtw04_4.sys`
- **Size:** 8756304 bytes
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

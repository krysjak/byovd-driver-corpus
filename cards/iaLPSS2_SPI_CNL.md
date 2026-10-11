# `iaLPSS2_SPI_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `503BBB5153F588A919F17E991D67D1988445724B28F0154072FF63E96AEAE1E6` | `22DBBCBB9272ED835B3EC91DD1FA263F951E344B` | `2D1BB7A9DB8993A1441043A79D15EBA5` |

## Metadata

- **Filename:** `iaLPSS2_SPI_CNL.sys`
- **Size:** 156936 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO SPI Driver v2
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

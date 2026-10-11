# `iaLPSS2_SPI_ADL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2_SPI_ADL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `93286B86DB6CCAB700C950FDCE1E30A597440C9CA017E0CBD053AD7789BC774D` | `B7DB16A79F41BC8F132502579586CC52B7440C01` | `26D25F8D8FDEF64E20AC9E3101C6C88C` |

## Metadata

- **Filename:** `iaLPSS2_SPI_ADL.sys`
- **Size:** 171608 bytes
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

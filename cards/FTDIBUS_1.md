# `FTDIBUS_1.sys`

[Back to index](../README.md) · [Українська версія](FTDIBUS_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `31868BCEE581B6CA2916D7424A6E2D36BEADD42F87C488C6A2F9725FD4A71CDF` | `EA477D2436F0C52F0780FB3D71784154FFEEA471` | `1079AF0DD98E56BDE579E3B4290D2536` |

## Metadata

- **Filename:** `FTDIBUS_1.sys`
- **Size:** 115416 bytes
- **Architecture:** 0x8664
- **Company:** FTDI Ltd.
- **Product:** FTDIChip CDM Drivers
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

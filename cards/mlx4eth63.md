# `mlx4eth63.sys`

[Back to index](../README.md) · [Українська версія](mlx4eth63.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B2CBDB7E4FBA8C1F59B1FE4AD02FBCE7EF514781FA7FAEF5C368F457E63D1A9F` | `C47E2F07BA31D8AECF74335DE4895934DFF912A1` | `9E3B1BDC7E8B84E5DC2331BA71CBBDDD` |

## Metadata

- **Filename:** `mlx4eth63.sys`
- **Size:** 709952 bytes
- **Architecture:** 0x8664
- **Company:** Mellanox
- **Product:** MLNX_EN
- **Description:** Mellanox ConnectX 10Gb Ethernet Adapter NDIS 6.60 driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `tbt100x.sys`

[Back to index](../README.md) · [Українська версія](tbt100x.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1DC616577ADD7845A27FE63CD0398704B1EC00095ED06C8B35FB556BD1BE720E` | `98BBBF8E62F4E06B8EB297244F19027DFA402D30` | `561D9298C3BC0D6E191300F8DD4B8414` |

## Metadata

- **Filename:** `tbt100x.sys`
- **Size:** 137680 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
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

# `ocnd65.sys`

[Back to index](../README.md) · [Українська версія](ocnd65.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `617FE6326D478FB61827B8161D163EF2C7DE2D5D404507922C48DC7935FF9FFA` | `AB38552BB1E4F93BC0041FADE7B121286019A1EF` | `ABED910E061820030BB868112825250A` |

## Metadata

- **Filename:** `ocnd65.sys`
- **Size:** 531376 bytes
- **Architecture:** 0x8664
- **Company:** Emulex
- **Product:** Emulex NDIS 6.40 miniport (x64)
- **Description:** Emulex Win10 NDIS 6.40 Miniport (x64)
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

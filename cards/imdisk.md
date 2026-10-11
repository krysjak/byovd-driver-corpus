# `imdisk.sys`

[Back to index](../README.md) · [Українська версія](imdisk.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9840607B61897ACBC5AF13F12D013494D0507E0A80E9BE063525BCB22369B560` | `409E03F912D7822DFE63DA2CD739BF92A2563C73` | `E8F81F9BA6245ECAE906957117CD7204` |

## Metadata

- **Filename:** `imdisk.sys`
- **Size:** 63976 bytes
- **Architecture:** 0x8664
- **Company:** Olof Lagerkvist
- **Product:** imdisk
- **Description:** ImDisk Virtual Disk Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

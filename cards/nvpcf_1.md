# `nvpcf_1.sys`

[Back to index](../README.md) · [Українська версія](nvpcf_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ED0F3F9C06A16444861A45BC0AC7F18BA40AA71DE47D8EEEB4A3EE03326FDA42` | `7D00FAE23FFA6830C0C57B59B21859D608EB0ADB` | `14844F94AE522872C0C6997A69217C5B` |

## Metadata

- **Filename:** `nvpcf_1.sys`
- **Size:** 239136 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVPCF
- **Description:** NVIDIA Platform Controllers and Framework
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 115

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

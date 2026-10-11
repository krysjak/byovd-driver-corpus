# `nvpcf_2.sys`

[Back to index](../README.md) · [Українська версія](nvpcf_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A910336BF9627EA89600A7A08A96E25DD615C46C8DE2680FEA817D6DFDD2D1F` | `AFB2A2FB04F27B4062B72D283A38673A7F9F0EE1` | `B48EBE042D80D374973887A807FB4D74` |

## Metadata

- **Filename:** `nvpcf_2.sys`
- **Size:** 235016 bytes
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

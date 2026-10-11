# `GSCAuxDriverx64.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C215CEFF62CA811CA55986E6646E9CCF6C8891CCFE6519862039CD7B7886D606` | `966F09BD5A48FBEC99F7D9F4762B025EF6E9F4CF` | `8D76875C9E13C70D167ACA9F5F435402` |

## Metadata

- **Filename:** `GSCAuxDriverx64.sys`
- **Size:** 85728 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Description:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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

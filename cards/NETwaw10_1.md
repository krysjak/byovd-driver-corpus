# `NETwaw10_1.sys`

[Back to index](../README.md) · [Українська версія](NETwaw10_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `331439D432E7D53B9BD0929E50D11AFDC762CA7383BC6A571349197F9E7BC2CC` | `97F6DB3950BDC592A8180A7E93A68430FB7FDA39` | `BF878FC86FEB2379C60AD6A26902E009` |

## Metadata

- **Filename:** `NETwaw10_1.sys`
- **Size:** 5040728 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** R Intel Wireless WiFi Link Driver
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

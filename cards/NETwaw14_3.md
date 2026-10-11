# `NETwaw14_3.sys`

[Back to index](../README.md) · [Українська версія](NETwaw14_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `621F95DD3906311DC38289843A7B443026BDCA98F8ABF80F4822C0B1E0C2C2B1` | `5343D28E079300AC3F925E7A1E89ABBF439FF39D` | `30257C8390DBD717E6972BCB7154DBD9` |

## Metadata

- **Filename:** `NETwaw14_3.sys`
- **Size:** 5590088 bytes
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

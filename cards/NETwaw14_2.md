# `NETwaw14_2.sys`

[Back to index](../README.md) · [Українська версія](NETwaw14_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D4C1A18F95725EB0388BB197D685A663886E59D0CCA3829D642C9E0C097B00D` | `AD591B71BDAAE2AB34BB5DCE2AFDA899A861CFAC` | `D87E5FF24AB53A5EE69EA17C8A4F80BB` |

## Metadata

- **Filename:** `NETwaw14_2.sys`
- **Size:** 5414568 bytes
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

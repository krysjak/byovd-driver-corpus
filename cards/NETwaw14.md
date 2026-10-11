# `NETwaw14.sys`

[Back to index](../README.md) · [Українська версія](NETwaw14.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `462BDA4751A0284F5FF7C9CCC6C4611A3849AA17BB2C76A196BA2630676EF61B` | `82448E275208637A85EBD65F9CD9AB76BED54E8D` | `0E7951F34C7F3818665175F2CFC31CDA` |

## Metadata

- **Filename:** `NETwaw14.sys`
- **Size:** 5593504 bytes
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

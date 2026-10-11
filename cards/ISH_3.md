# `ISH_3.sys`

[Back to index](../README.md) · [Українська версія](ISH_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `73C4ECB45F6D82BAF194CD0E0297CCC13D2CAF2238E1811716BC95BA684456EB` | `2C3937D04E7C6403E3FBA9E929A2D2D548D810E3` | `69EBCAD2DAB8626CE3F95775FD42350A` |

## Metadata

- **Filename:** `ISH_3.sys`
- **Size:** 158096 bytes
- **Architecture:** 0x8664
- **Company:** Intel
- **Product:** ISS
- **Description:** Intel(R) Integrated Sensor Solution
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

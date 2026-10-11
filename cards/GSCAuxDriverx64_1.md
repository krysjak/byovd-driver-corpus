# `GSCAuxDriverx64_1.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F936A819638AF4EF4E01A0AAA56A7C3652E73C34CAB50489F793655ACE952281` | `0F279583AEC244461C00C36F03380971F2781768` | `5C6A2D2F6B1C7AEFDBEC7E6033BF019D` |

## Metadata

- **Filename:** `GSCAuxDriverx64_1.sys`
- **Size:** 76048 bytes
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

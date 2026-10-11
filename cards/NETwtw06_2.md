# `NETwtw06_2.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B70DEF092662497EB69EF0E9A525DCB2D91F3BFD90780D5DF832B193E9729E13` | `821196CE47CC2C90A9E1CF714F0DF891498835DA` | `B86397588E784D7077E09BE6A395864D` |

## Metadata

- **Filename:** `NETwtw06_2.sys`
- **Size:** 8903248 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
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

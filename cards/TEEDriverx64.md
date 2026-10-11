# `TEEDriverx64.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverx64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `10C193D1ED434A6DC2AD8C450012B9AF1C848A0A0B3B775F13495648FB77E009` | `092D2AF6AAFA27056AC5B6BD1D73511B3C6639D4` | `E0EF6C1399A9B1AAA0B28590411BED04` |

## Metadata

- **Filename:** `TEEDriverx64.sys`
- **Size:** 99288 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
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

# `Netwsw00.sys`

[Back to index](../README.md) · [Українська версія](Netwsw00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3D65A772C15440DF5895843185241D890CCDECA0E02DD6CF32CCB9B5849E31A4` | `90ECD5A5E941D8AAEDE618B6C472198699D509FD` | `272BB8C52BE106B5CC69171AF1D281D4` |

## Metadata

- **Filename:** `Netwsw00.sys`
- **Size:** 11518976 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

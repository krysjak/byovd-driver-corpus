# `NETwew01.sys`

[Back to index](../README.md) · [Українська версія](NETwew01.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `801C2A1F12E6F0D646E92C98477FCDB84C6743803CD7365B774B0F88EB650584` | `D2A7B08D6A92C081B12924FA6B2B7D6EF6426C17` | `99C24A7DC1F3D4845553B4BD189274A0` |

## Metadata

- **Filename:** `NETwew01.sys`
- **Size:** 3343872 bytes
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

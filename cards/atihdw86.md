# `atihdw86.sys`

[Back to index](../README.md) · [Українська версія](atihdw86.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E3E0D1DD072637302731B8A60B38219C419D9BF8DF127D5B811750FBBC8FD3AB` | `6F3D4EC22CE632764BFDFADB3E159986023C9F02` | `FAFEB8F172171C471922C6D114CAA3A1` |

## Metadata

- **Filename:** `atihdw86.sys`
- **Size:** 215040 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
- **Signature:** unsigned
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `NETwtw06_4.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D4524466E6D66BC990883ED9D78CB89A9ED50AE4A0583372D142989519A1FF4` | `89725B611FBED0D39381A839C72974859269DA6B` | `FF2256FA6C9A1AA8CA13D768FD09C489` |

## Metadata

- **Filename:** `NETwtw06_4.sys`
- **Size:** 8831480 bytes
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

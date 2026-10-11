# `netwlv64.sys`

[Back to index](../README.md) · [Українська версія](netwlv64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DB6AD436A4AF7D94F8BB3159EF0E0A34AD93F9419957FF8AFC9978FB664CD3FF` | `B0B8B196300965031234A42BFB052700CEB830F9` | `10C475C8374F5E4905979D6C5F504DE0` |

## Metadata

- **Filename:** `netwlv64.sys`
- **Size:** 7530496 bytes
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

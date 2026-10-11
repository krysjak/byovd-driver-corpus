# `IntcAudioBus.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `07AE13A88DB54A1F0BE267921F53A532753BA951F122A9540DDFF0E66C6C7E80` | `BC1759C3402D16EA7BA635E3146E27EFA94C5ED4` | `6AD4DBBD2F79CE34AB323E988C3C873B` |

## Metadata

- **Filename:** `IntcAudioBus.sys`
- **Size:** 314880 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Description:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

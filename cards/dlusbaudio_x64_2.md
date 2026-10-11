# `dlusbaudio_x64_2.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_x64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B44CECF63298A7E124C5AAD7432F0731AE8818BD3CFBAF7BBA42793F75746FE6` | `7DD0733CCBC8901F9DD670A13F5A3E1C1C7A72EF` | `C0042D5EF14E2CB44D23B2C4E5D687A9` |

## Metadata

- **Filename:** `dlusbaudio_x64_2.sys`
- **Size:** 229744 bytes
- **Architecture:** 0x8664
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

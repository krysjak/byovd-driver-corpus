# `dlusbaudio.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `910E1BD4099BAF59304E5C71D8CB806F8DE380A1A57B9D6FF6900169B8453820` | `E259C434C6CC498807E4ADF2D24D2D6AD627D963` | `4585CB5CA4711D9D8BFB1CD6BFF25029` |

## Metadata

- **Filename:** `dlusbaudio.sys`
- **Size:** 176344 bytes
- **Architecture:** 0x14c
- **Company:** DisplayLink Corp.
- **Product:** DisplayLink USB Audio 2.0 Class Driver
- **Description:** DisplayLink USB Audio Driver
- **Signature:** signed
- **Source:** `oem:dell`
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

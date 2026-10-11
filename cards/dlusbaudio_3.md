# `dlusbaudio_3.sys`

[Back to index](../README.md) · [Українська версія](dlusbaudio_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D0E621AD7FBAC75061B460C59026E5F2B840B01B4F46D13DCD651CEC87EEB967` | `84E7FF6DD3A2F3C598253E682F44C3484F1298E9` | `147CF0256EC0BC39412ADBC43163A404` |

## Metadata

- **Filename:** `dlusbaudio_3.sys`
- **Size:** 168264 bytes
- **Architecture:** 0x14c
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

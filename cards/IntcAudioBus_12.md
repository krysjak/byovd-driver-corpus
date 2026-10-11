# `IntcAudioBus_12.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_12.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9F935B5D232771FC1DC4C4352CC3B3945B094C12D8C00C3854FEB25B581149B0` | `E967E633A949F5935E83F4FD906FFCE681E17611` | `754683F220721E84FDAF6C641BB21CB3` |

## Metadata

- **Filename:** `IntcAudioBus_12.sys`
- **Size:** 292432 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Description:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Signature:** signed
- **Source:** `oem:hp`
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

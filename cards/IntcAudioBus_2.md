# `IntcAudioBus_2.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `32FF3F79A95935EFEEFF65076CCC3E39D0011DFD447CD84C807677E0CD202385` | `BD2BE7705DCD95631FA685546C940EA52CA1A25C` | `6838AD7A98E9721F98070E87171D578F` |

## Metadata

- **Filename:** `IntcAudioBus_2.sys`
- **Size:** 261600 bytes
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

# `IntcAudioBus_9.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `77EE4DD8AFA92E656563D243519C0E12EFCAF6B483AC8AA81FFDCFCE3C5D0B0C` | `6BBBB9A249227FC01ABBF99FA15EE827140C8C78` | `7963B5F1304EBB1117B7DEC10D81982D` |

## Metadata

- **Filename:** `IntcAudioBus_9.sys`
- **Size:** 302872 bytes
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

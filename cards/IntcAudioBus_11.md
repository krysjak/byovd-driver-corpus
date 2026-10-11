# `IntcAudioBus_11.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_11.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA5D67C82CE1EF3B4ACF0A440C32C1645F00522B0F456BD77EDEADCF80D08A16` | `719A586B80F62587C1A2561A3C9AC981006C8E65` | `AD8F45812409D4B464736A78F62BABA3` |

## Metadata

- **Filename:** `IntcAudioBus_11.sys`
- **Size:** 229464 bytes
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

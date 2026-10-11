# `IntcAudioBus_6.sys`

[Back to index](../README.md) · [Українська версія](IntcAudioBus_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `17CAB5D27EDCBEBDA9539A17710BEA7A8D649A596D80046E390D30AFA5FE4D3B` | `28C8A99F4DED2AA2B9429216C3219FBD2FE40EAC` | `FBED23189F8FB107DBCC25C0FB224AA7` |

## Metadata

- **Filename:** `IntcAudioBus_6.sys`
- **Size:** 292936 bytes
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

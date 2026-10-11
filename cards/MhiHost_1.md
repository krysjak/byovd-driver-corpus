# `MhiHost_1.sys`

[Back to index](../README.md) · [Українська версія](MhiHost_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37786975366D40263A730985E33D4832E87529EBD12ECD922F423EC9B3A27D45` | `9D37C09187D8A1A1C5E6E8988789DD4FD3F10D7D` | `323C6ECECFC4A583D9D2D2CC5BBE9934` |

## Metadata

- **Filename:** `MhiHost_1.sys`
- **Size:** 213808 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Technologies, Inc.
- **Product:** Qualcomm Modem Host Interface Driver
- **Description:** QUALCOMM Modem Host Interface Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

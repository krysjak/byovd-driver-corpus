# `TbtBusDrv.sys`

[Back to index](../README.md) · [Українська версія](TbtBusDrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C487612D8207F791400086A052A6B11781D8831809565B13E5081B6113F14ACC` | `9B68FDEBB9D173BBC825D35FAF1932BE53DDE6E7` | `7DB011D7110C30ED773D97435107FDE6` |

## Metadata

- **Filename:** `TbtBusDrv.sys`
- **Size:** 3183200 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

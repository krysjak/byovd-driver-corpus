# `IntcOED_9.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B3CF1AEB96F2E92E265A55FAEBD84C71DD958C6D037BB5A9FC994A92758BFC38` | `46FC5959B2BB673D32C156A47A1B84014226481F` | `BF63C148FD3C50EDF6F5BAD740270D90` |

## Metadata

- **Filename:** `IntcOED_9.sys`
- **Size:** 1278200 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel® Smart Sound Technology (Intel® SST) OED
- **Description:** Intel® Smart Sound Technology (Intel® SST) OED
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

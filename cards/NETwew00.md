# `NETwew00.sys`

[Back to index](../README.md) · [Українська версія](NETwew00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `71D6AC59541091FA8D7B421E360075916CCFE20B6CF68D15E4D9224F05616D91` | `7CAAB6412FA512D1EBD19A84B5E3C493D6556200` | `F10285CEF995267A865988E1B44CF7EC` |

## Metadata

- **Filename:** `NETwew00.sys`
- **Size:** 3341824 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

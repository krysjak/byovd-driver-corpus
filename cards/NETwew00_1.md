# `NETwew00_1.sys`

[Back to index](../README.md) · [Українська версія](NETwew00_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `98E8C8450C62047264C36E11E58EC11897FCD9DFCA443787521AA41CBD39E562` | `1B96B55B4D06EEE721B11E9FDA922BCD7A409F75` | `B1BA612CA1D2AE9BB5B0B8C0AE08235D` |

## Metadata

- **Filename:** `NETwew00_1.sys`
- **Size:** 3352336 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
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

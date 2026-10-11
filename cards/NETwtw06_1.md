# `NETwtw06_1.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `32B892577666433B4641B7D048EC96B52AA0752F3CE92CDFD2D8F0E25C7314FB` | `2CA9A84DFC0024995CEDA27E1251D654231ACCE7` | `3553CA8929F723ED63C9AF8AA98989C5` |

## Metadata

- **Filename:** `NETwtw06_1.sys`
- **Size:** 8809320 bytes
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

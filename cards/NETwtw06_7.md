# `NETwtw06_7.sys`

[Back to index](../README.md) · [Українська версія](NETwtw06_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F0E3AD25872EBB6F464F5A28E6EEE9415FA5155CC19BDB53D8DE9B868F168E7` | `62993382A0EE4105F850E11E19CD13080565B1B2` | `E1F050351D6A5787D78555A4C24ADF9F` |

## Metadata

- **Filename:** `NETwtw06_7.sys`
- **Size:** 8822392 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:hp`
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

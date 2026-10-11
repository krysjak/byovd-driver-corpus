# `NETwNs64.sys`

[Back to index](../README.md) · [Українська версія](NETwNs64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `898DCBBBF94875059CD328B0FC75BE36A4E3DD471C6E28BFAE064BCF84349518` | `DEA0FEECC37BDBA5FD2845B3A0CB5C6FEFF1F5E3` | `57B9C04D673F236D41FAB03842C8640B` |

## Metadata

- **Filename:** `NETwNs64.sys`
- **Size:** 8604672 bytes
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

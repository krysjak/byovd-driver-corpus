# `Netwbw02.sys`

[Back to index](../README.md) · [Українська версія](Netwbw02.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8CB13863C1F0C589C008E191A393DF241F3067DD7CADE02B3B7D36B28BBA2ED` | `C0541D17C4B0293FC97F20F46E53CEF6D606B9FC` | `1F91B1E5FD41BDC3DF8AFFB81C8AA277` |

## Metadata

- **Filename:** `Netwbw02.sys`
- **Size:** 3485696 bytes
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

# `Netwen02.sys`

[Back to index](../README.md) · [Українська версія](Netwen02.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0FA9A79E129EF6F1AABA736A171E2C48CEBA07447206110A3096DE59474C3779` | `68CFA7B76AFA7528549502DA9FBEBB8D27486E78` | `6D4D255973E2B002160E62986E7369DF` |

## Metadata

- **Filename:** `Netwen02.sys`
- **Size:** 2964448 bytes
- **Architecture:** 0x14c
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

# `NETwtw02_1.sys`

[Back to index](../README.md) · [Українська версія](NETwtw02_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D14E800C05992A7AE960F8A7C7986234A934D3F55D0F7DA45C66367B969D931` | `FFDB69508DFEFB77929E3DB8D886AB5E2942A165` | `A223E3862DDB449F61A25C222D292C23` |

## Metadata

- **Filename:** `NETwtw02_1.sys`
- **Size:** 6723848 bytes
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

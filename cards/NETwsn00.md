# `NETwsn00.sys`

[Back to index](../README.md) · [Українська версія](NETwsn00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9AD4AADA40FA8F43955834C6326DDB887FCAE7615CC4937A80FD60A4E0E7A42A` | `52F7A76E1C41E7E5FCF3533668ADBD21CB7A46DD` | `47613E9D8330024D08BF4BC10A43BF07` |

## Metadata

- **Filename:** `NETwsn00.sys`
- **Size:** 10382576 bytes
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

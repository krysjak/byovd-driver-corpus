# `NETwaw18.sys`

[Back to index](../README.md) · [Українська версія](NETwaw18.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9ACA0B7EBCEF5A63828496A98D22522A2D25990D5C816863340708C271A9926F` | `42D412110C189DB357E6FA0A121D2C21BC20C14C` | `84EC8A74647F3F07D8F1CEABC25682C0` |

## Metadata

- **Filename:** `NETwaw18.sys`
- **Size:** 5965216 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** R Intel Wireless WiFi Link Driver
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

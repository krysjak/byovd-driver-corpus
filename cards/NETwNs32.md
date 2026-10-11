# `NETwNs32.sys`

[Back to index](../README.md) · [Українська версія](NETwNs32.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `494D5F5EE070E1BD719B9A50B11EE15DC4297C9D86B30C24579F782CEEF9100A` | `88219AC6C60CE73500FFBFB909D6E5FF966AB42C` | `D98BD0F579FE745CEF75E87EA88C4775` |

## Metadata

- **Filename:** `NETwNs32.sys`
- **Size:** 7530736 bytes
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

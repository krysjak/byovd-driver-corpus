# `NETwtw08_9.sys`

[Back to index](../README.md) · [Українська версія](NETwtw08_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1842F1028A5F5356A090E744A956A6917E8EFF75E10C523BA24244CC8648FE3E` | `697C4A0C58D24431502B4B937BA95C7C135BC18D` | `8E143210A4FE196A62575AE93A5F7B76` |

## Metadata

- **Filename:** `NETwtw08_9.sys`
- **Size:** 9276192 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** Intel® Wireless WiFi Link Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

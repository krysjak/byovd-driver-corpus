# `NETwtw08_1.sys`

[Back to index](../README.md) · [Українська версія](NETwtw08_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4159F53FD4A5B6BBD7ACE0B395A532342DDBA49799B7DC78B6CAB589D620EED9` | `5CB0F4069C927CD9ACBF7C67840B47BCC169FE1D` | `3AD1073BFA135670EAC090C6E78A86CA` |

## Metadata

- **Filename:** `NETwtw08_1.sys`
- **Size:** 8922528 bytes
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

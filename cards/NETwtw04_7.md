# `NETwtw04_7.sys`

[Back to index](../README.md) · [Українська версія](NETwtw04_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `11DDEADCBA88EE12A96B22409D16494D86262D3F315E908756E034484FD14966` | `6FEDE059A17BFB218C03928806BAAC683FB32949` | `8AB86BAB99B5B6CD96EBAB279EB43B72` |

## Metadata

- **Filename:** `NETwtw04_7.sys`
- **Size:** 8717808 bytes
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

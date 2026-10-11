# `NETwtw08_13.sys`

[Back to index](../README.md) · [Українська версія](NETwtw08_13.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B49E5820DE04FF4918A9C7511ED887ABCD2ABF2A2001BA57E5E82552C054EDA1` | `37E14933CF39386DDB9EFE9527FB815149090624` | `CF75BDE25CC440FD0A2A0FCBA2D2A63D` |

## Metadata

- **Filename:** `NETwtw08_13.sys`
- **Size:** 8964216 bytes
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

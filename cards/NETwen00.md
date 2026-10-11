# `NETwen00.sys`

[Back to index](../README.md) · [Українська версія](NETwen00.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `54C4942BF73EAE73CE62D256529EB20F4E48E4C9468E8235AA0AE6263212EE5B` | `28774098B54803A92BD8FEEEE558FCE2A3AAC3A2` | `B59A695291BA2996324042C24AA880DE` |

## Metadata

- **Filename:** `NETwen00.sys`
- **Size:** 2672608 bytes
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

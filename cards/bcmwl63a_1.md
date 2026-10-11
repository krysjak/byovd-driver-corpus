# `bcmwl63a_1.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63a_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3581B68F147D37BE4B482A18291E91AAD8340A1BF512485FD87508EB435EB0DF` | `7E016D0DCD721EE96F1334E5C6DA1093002AB9F2` | `1465EFCC24785AF61D24E791E285CA09` |

## Metadata

- **Filename:** `bcmwl63a_1.sys`
- **Size:** 11703560 bytes
- **Architecture:** 0x8664
- **Company:** Broadcom Corp
- **Product:** Broadcom WiFi Driver wireless driver
- **Description:** Broadcom WiFi Driver wireless driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

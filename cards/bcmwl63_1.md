# `bcmwl63_1.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0C05EF5C9028D374FF1D91993AD5A2C83CEEC3588AE119A550781E9906EACA9B` | `92050E7A357175B2ECC50126617113E32EE38025` | `E8B2717A4387C7E57FE771F84C18A6DE` |

## Metadata

- **Filename:** `bcmwl63_1.sys`
- **Size:** 10866944 bytes
- **Architecture:** 0x14c
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

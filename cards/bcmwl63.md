# `bcmwl63.sys`

[Back to index](../README.md) · [Українська версія](bcmwl63.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BD9A9F370B47C58FE424E8D95E3D1505520DCE4BBE98B87F23C7701352A6460` | `33D21B0CB57B653CAB095882B6006272FBBA0BA5` | `D1D29204E4738A68C7E909988D8EC084` |

## Metadata

- **Filename:** `bcmwl63.sys`
- **Size:** 10768136 bytes
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

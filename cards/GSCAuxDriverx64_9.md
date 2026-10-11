# `GSCAuxDriverx64_9.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_9.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9D7E2627BBE5F330E43D2C33EABA7347B368D85CD4AA63459086A8965FCAE018` | `12E867B316DF63B99D45D6AD0D5D0F7861F9003A` | `8829EE3E6C6A335C10C45D874D2FE809` |

## Metadata

- **Filename:** `GSCAuxDriverx64_9.sys`
- **Size:** 78912 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Description:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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

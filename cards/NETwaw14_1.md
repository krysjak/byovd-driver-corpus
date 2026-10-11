# `NETwaw14_1.sys`

[Back to index](../README.md) · [Українська версія](NETwaw14_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A7D23C237578E5811D8C131681C9AD5182D8BA902E6CED3A31D62830ED5373C8` | `2DDB96ACBB2119B05E0153DE36490FE5163353EB` | `2FF5513ED3335A0DF3D8FECC8AAF75C6` |

## Metadata

- **Filename:** `NETwaw14_1.sys`
- **Size:** 5612984 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless WiFi Link Adapter
- **Description:** R Intel Wireless WiFi Link Driver
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

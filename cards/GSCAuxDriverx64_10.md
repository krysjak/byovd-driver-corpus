# `GSCAuxDriverx64_10.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5AEA23AA8C8E0B1E0D01FE6B24BB7D02540BC40812DB2EF3234DE81E275E8E54` | `FDB0A44E5F66B2C2504459587114C686B5EEE51C` | `1C91B5CDD66B4B37C47823C00E0038D3` |

## Metadata

- **Filename:** `GSCAuxDriverx64_10.sys`
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

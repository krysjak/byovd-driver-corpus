# `GSCAuxDriverx64_8.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_8.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `17D058085BF607710F97BE9C254FBB80AA9806D38A7A7857E0CF1992FF1AFE99` | `27D6673D86414BD166470FD3735FCB15D11A8CC6` | `0FEB7EA2C0C13FAC209531FE8D57F199` |

## Metadata

- **Filename:** `GSCAuxDriverx64_8.sys`
- **Size:** 86072 bytes
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

# `GSCAuxDriverx64_2.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D3145D102584447B0DADF74E4B7A9CEED248EC7EA06C0BCA5C8BBFAB0307FA44` | `1621FA52CAE6EAC01A466337DA39B626531C23CB` | `D8A4B918367064A2AE475D9E4CB22920` |

## Metadata

- **Filename:** `GSCAuxDriverx64_2.sys`
- **Size:** 102328 bytes
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

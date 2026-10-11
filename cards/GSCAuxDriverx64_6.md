# `GSCAuxDriverx64_6.sys`

[Back to index](../README.md) · [Українська версія](GSCAuxDriverx64_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27EAC7BC4C03A05E3F6E8EAB3A022C6A0A21C37F51298535FD83D5CE83876D96` | `93BFA94F7CB4DBCBAB87FC7E8F15790D2718916D` | `9D68DD1B98C9AB6C157998A8D2376CFF` |

## Metadata

- **Filename:** `GSCAuxDriverx64_6.sys`
- **Size:** 109256 bytes
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

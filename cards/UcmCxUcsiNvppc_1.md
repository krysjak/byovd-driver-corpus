# `UcmCxUcsiNvppc_1.sys`

[Back to index](../README.md) · [Українська версія](UcmCxUcsiNvppc_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `01736D4B848B3614EA4F88985C7836E6403794A3D769DDCF9597F868F75B29FC` | `D58478D2A781B8A18CA8419A1DBFD3A1D4D7CDAE` | `BADAB706325D4DC994F9934FC6BF3222` |

## Metadata

- **Filename:** `UcmCxUcsiNvppc_1.sys`
- **Size:** 715296 bytes
- **Architecture:** 0x8664
- **Company:** NVIDIA Corporation
- **Product:** NVPPC
- **Description:** NVIDIA PPC Function Driver.
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

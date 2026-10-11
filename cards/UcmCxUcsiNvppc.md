# `UcmCxUcsiNvppc.sys`

[Back to index](../README.md) · [Українська версія](UcmCxUcsiNvppc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `23853223F434BC3BCCEC7FB1BC1F974E87E7032B41CB588BBD1B44C30952FECD` | `ECFA5F51C661AC60162F68744D1BBB7C78C6682C` | `5C100BA18C44C4F8D36211284B5F4C1D` |

## Metadata

- **Filename:** `UcmCxUcsiNvppc.sys`
- **Size:** 709008 bytes
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

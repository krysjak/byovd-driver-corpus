# `acpi_2.sys`

[Back to index](../README.md) · [Українська версія](acpi_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D69D673224EB9F899180E2D3CC32DA12AE8299437D51EBC2D8E96266B4C33DA0` | `9EC1E7F82EF2D3CF4004743DFB4A72D88B1F8DBC` | `8905324CCD30FBE5AF95C0B652ED71DE` |

## Metadata

- **Filename:** `acpi_2.sys` (Identical copies: `acpi_3.sys`)
- **Size:** 873856 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** ACPI Driver for NT
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 140

## Capability profile

**Primitives:** `driver loading`, `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

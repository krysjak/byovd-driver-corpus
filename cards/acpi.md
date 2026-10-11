# `acpi.sys`

[Back to index](../README.md) · [Українська версія](acpi.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D3AA14F018867348959FB3006B7D1EE16496FDFF4DBF358CD0A0A17E61AB5DF` | `4B75CCAC8E7684FEB61262F2D24446F109ADED7D` | `2F4F3194C2A24D89FE40564488DB2AD4` |

## Metadata

- **Filename:** `acpi.sys` (Identical copies: `acpi_1.sys`)
- **Size:** 873984 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** ACPI Driver for NT
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `driver loading`, `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

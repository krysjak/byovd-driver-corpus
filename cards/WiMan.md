# `WiMan.sys`

[Back to index](../README.md) · [Українська версія](WiMan.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `819C2F1CB0367B4C7A4CE6AD834E04647E5C3F4DB6CAE7B39D0F79C959C9EE0E` | `4A693AC2F6A55C78D475215E43ACC524D655C0ED` | `54C29AD4268F56C07351EB3CEA078F71` |

## Metadata

- **Filename:** `WiMan.sys`
- **Size:** 171952 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel® Wireless Manageability
- **Description:** Intel® Wireless Manageability
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

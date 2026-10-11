# `amd_dpfc_1.sys`

[Back to index](../README.md) · [Українська версія](amd_dpfc_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `19E48CE439C7CEE4658DF7D3ADD6371FC3D70E57F6D3934AEFDAAE0D615D2A44` | `02B59EB74F2B0EE8E8FD25C7867CEDFB697246FB` | `52948042F4374E1A60657264BCFD0F6B` |

## Metadata

- **Filename:** `amd_dpfc_1.sys`
- **Size:** 53120 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD Dynamic Power and Frequency Control Service Driver
- **Description:** AMD Dynamic Power and Frequency Control Service Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 105

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

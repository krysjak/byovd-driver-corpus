# `amd_dpfc.sys`

[Back to index](../README.md) · [Українська версія](amd_dpfc.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C134B5D0702231A72C97237CCF632BB5FE43FFDCEDD45F333D0FB6F7C7243AD` | `BE0E1DAA1A5EB849514229EFB2800F5AD72076B6` | `A22E152982CDD234FAA33FBD582E2A64` |

## Metadata

- **Filename:** `amd_dpfc.sys`
- **Size:** 58808 bytes
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

# `amd_dpfc_2.sys`

[Back to index](../README.md) · [Українська версія](amd_dpfc_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `852EEBACDBF7CC314B1FCE5560230B4AA9F23C16F41056ED6DA246E15ABE9A0F` | `DA10E94DC3A8F7F119B101BE87CEB43434978EF9` | `85708C3CB9CA2CAE50F5B65D9AD2B58D` |

## Metadata

- **Filename:** `amd_dpfc_2.sys`
- **Size:** 59072 bytes
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

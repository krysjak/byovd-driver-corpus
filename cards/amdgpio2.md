# `amdgpio2.sys`

[Back to index](../README.md) · [Українська версія](amdgpio2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `93DC48E60476F5D4DC456657387EF46E38D5E705F51B55543F044AA2F1E9E0F6` | `F518837135F8AC61919FA23D89BD54B31D67460D` | `3CFE13542AEE43E026DCBDAC0B556CFC` |

## Metadata

- **Filename:** `amdgpio2.sys` (Identical copies: `amdgpio2_1.sys`, `amdgpio2_2.sys`)
- **Size:** 53064 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD GPIO Controller Driver
- **Description:** AMD GPIO Controller Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

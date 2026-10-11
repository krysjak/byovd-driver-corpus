# `amdgpio2_3.sys`

[Back to index](../README.md) · [Українська версія](amdgpio2_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `46A53925BAA34FA9D87E7C3157504A4557D81CD8B8608E7AB6CAF02F482F7792` | `7A8D676BC87AED25822F303C7F2E2286FBAC5BBA` | `55578CF027B0AE9F0D653B209C9F1B6D` |

## Metadata

- **Filename:** `amdgpio2_3.sys` (Identical copies: `amdgpio2_5.sys`)
- **Size:** 18432 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMD GPIO Controller Driver
- **Description:** AMD GPIO Controller Driver
- **Signature:** unsigned
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 55

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

# `ISH_1.sys`

[Back to index](../README.md) · [Українська версія](ISH_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B9D675E8D0E47D3714B6A2FD8CE0D0470EE69F4A25B35607FE5E88FFBC2D66A2` | `2C25B83650146F2AF012F1B1E8088D10D1601610` | `EF49FFC12A54AB06AFACF3192412EA53` |

## Metadata

- **Filename:** `ISH_1.sys`
- **Size:** 161680 bytes
- **Architecture:** 0x8664
- **Company:** Intel
- **Product:** ISS
- **Description:** Intel(R) Integrated Sensor Solution
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

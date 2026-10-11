# `logi_joy_bus_enum.x64.sys`

[Back to index](../README.md) · [Українська версія](logi_joy_bus_enum.x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `79065269B2009DAE18CDF5D9090FE8BAB98DCFC1C52E66F91D62F47038192E9B` | `B9BA728EA1123AFD8189B547E6D0585CB2A5CB54` | `B1F1ED17A7098189A6A7B81304E783F5` |

## Metadata

- **Filename:** `logi_joy_bus_enum.x64.sys` (Identical copies: `logi_joy_bus_enum.x64_1.sys`)
- **Size:** 45448 bytes
- **Architecture:** 0x8664
- **Company:** Logitech
- **Product:** Logitech G Drivers
- **Description:** Logitech G Drivers
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

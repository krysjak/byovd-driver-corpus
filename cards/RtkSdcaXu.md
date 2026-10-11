# `RtkSdcaXu.sys`

[Back to index](../README.md) · [Українська версія](RtkSdcaXu.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0641267C2412E714052FDBFD5ED940111BE907F0E30BAC23CA0029B518A1ECFC` | `7EE9BF2599044A9D2A803DF739EE8C98F2B85937` | `D2E94DEA03E3C33840FDF80D19045E73` |

## Metadata

- **Filename:** `RtkSdcaXu.sys`
- **Size:** 687144 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek SDCA Extension Unit Driver
- **Description:** Realtek SDCA Extension Unit Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

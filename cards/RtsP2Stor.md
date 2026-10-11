# `RtsP2Stor.sys`

[Back to index](../README.md) · [Українська версія](RtsP2Stor.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E1B1251425081D43258D6F94AEDD3D77CCF4C28B05D79D87B755D6F4DD72CE` | `0117EF0F87BEBC0CED8E541E5C88ED870723580A` | `798330E809C5B3EDB2BA156533C57D1D` |

## Metadata

- **Filename:** `RtsP2Stor.sys`
- **Size:** 330176 bytes
- **Architecture:** 0x8664
- **Company:** Realtek Semiconductor Corp.
- **Product:** Realtek Pcie CardReader Driver for 2K/XP/Vista/Win7/Win8
- **Description:** Realtek Pcie CardReader Driver for 2K/XP/Vista/Win7/Win8
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 100

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

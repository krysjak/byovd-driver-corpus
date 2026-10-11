# `athw8x.sys`

[Back to index](../README.md) · [Українська версія](athw8x.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DE129E570C85EE8AAE8084B40F4E32766B4B789A2EED81E46311712B0826053D` | `E649EAC3D9680CD11D26C2F4C8EAC60040889BC6` | `835E2C1A3D32492E2B90BD4FE5527CB6` |

## Metadata

- **Filename:** `athw8x.sys`
- **Size:** 4233728 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Atheros Communications, Inc.
- **Product:** Driver for Qualcomm Atheros CB42/CB43/MB42/MB43 Network Adapter
- **Description:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

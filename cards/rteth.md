# `rteth.sys`

[Back to index](../README.md) · [Українська версія](rteth.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AD633FAB8A7B61337B9EF6AD7651F213BFEADC2CAA741AF95DBF20E5C3EC8BCE` | `E810F67F541FC664B3991F8A2D0E0B8DB25515B4` | `30993B838ACFB0F1D6F2B416A40BBA76` |

## Metadata

- **Filename:** `rteth.sys`
- **Size:** 86016 bytes
- **Architecture:** 0x8664
- **Company:** Realtek
- **Product:** Realtek PCIe GBE Family Adapters
- **Description:** Realtek PCIe GBE Family Controller Flight
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

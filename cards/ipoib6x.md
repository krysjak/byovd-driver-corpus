# `ipoib6x.sys`

[Back to index](../README.md) · [Українська версія](ipoib6x.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `585BF746BF943E5F0FD09C6CF3B96643BB1E4B9D0489D205E11A99F7742E6444` | `0EC1D57A625E5407113FD253130909700AB1CEEE` | `A73BA5D0E080002650F0FFFFF01C4DFE` |

## Metadata

- **Filename:** `ipoib6x.sys`
- **Size:** 579376 bytes
- **Architecture:** 0x8664
- **Company:** Mellanox
- **Product:** MLNX_EN
- **Description:** Mellanox ConnectX based IPoIB Adapter ( NDIS 6.4) Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

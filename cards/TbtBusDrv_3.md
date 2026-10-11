# `TbtBusDrv_3.sys`

[Back to index](../README.md) · [Українська версія](TbtBusDrv_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E7E3C3E18E928D2B7E81FC5609E1D4F20029C45E642C26EADEA6DCFF98D22C2F` | `650A2F5EC372992368533B962E67DC9DA93E618E` | `92B3681E40DE5A34688433F8C568CA66` |

## Metadata

- **Filename:** `TbtBusDrv_3.sys`
- **Size:** 2552272 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Thunderbolt(TM) Bus Driver
- **Description:** Thunderbolt(TM) Bus Driver
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

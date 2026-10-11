# `ISH_4.sys`

[Back to index](../README.md) · [Українська версія](ISH_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B45D4E221F48221541E3844A9362AC364D1D8143B6ED70A338BBA8E89FBED6E7` | `C1E769E32BA1F177BCCFD49F9CC433B183F95398` | `AFDAC4240145325D526114A0D9E50A8A` |

## Metadata

- **Filename:** `ISH_4.sys`
- **Size:** 175232 bytes
- **Architecture:** 0x8664
- **Company:** Intel
- **Product:** ISS
- **Description:** Intel(R) Integrated Sensor Solution
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

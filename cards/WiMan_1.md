# `WiMan_1.sys`

[Back to index](../README.md) · [Українська версія](WiMan_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8381275F6E99739F29602AEDD2D5DA3B7F870398D62ABAF496EF0E25733F02EE` | `1EE10D47DAF1A16488503F2BEE4F6F35DC56ADF7` | `99E5B972F16C8E6CF00BADBBEF1DB729` |

## Metadata

- **Filename:** `WiMan_1.sys`
- **Size:** 165224 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

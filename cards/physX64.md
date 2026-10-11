# `physX64.sys`

[Back to index](../README.md) · [Українська версія](physX64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DA3C4D837D873085531337A99484115563ACE01A5A1085A3C0160582B480034F` | `180FC3844BE7703CF0635D1AFBE78DE71C0DB72B` | `7C0B34E30F62110CCEBC2F09BF79869C` |

## Metadata

- **Filename:** `physX64.sys`
- **Size:** 148768 bytes
- **Architecture:** 0x8664
- **Company:** AGEIA Technologies, Inc.
- **Product:** AGEIA PhysX Processor WDM Driver
- **Description:** AGEIA PhysX Processor WDM Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

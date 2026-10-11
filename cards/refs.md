# `refs.sys`

[Back to index](../README.md) · [Українська версія](refs.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C92FC9181B31980E04D96A14C56925C45F7ACF6D90E3E2E00750D4DFFA119BA` | `518BE8E606DC383B10C9D616948420A11C26FBB9` | `4FE0FF494A0BF08119BE4A135066FF4B` |

## Metadata

- **Filename:** `refs.sys`
- **Size:** 3528168 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** NT ReFS FS Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

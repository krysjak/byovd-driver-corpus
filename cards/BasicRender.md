# `BasicRender.sys`

[Back to index](../README.md) · [Українська версія](BasicRender.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CBAC7C00AC64C28FA56B735AB4065C9D95FCB992F84B00100309F8737DAA819D` | `5BD4FBD608CD1EDE801045B2BB87297B540A8CDE` | `62E82D0E4C5E72546747A0C97612509A` |

## Metadata

- **Filename:** `BasicRender.sys`
- **Size:** 73728 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft Basic Render Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `process address-space attach`, `process handle access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwLoadDriver`, `ZwOpenProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

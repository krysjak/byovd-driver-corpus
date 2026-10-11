# `netcxrd_1.sys`

[Back to index](../README.md) · [Українська версія](netcxrd_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD1198516A5576AF702DCD833E0EE3F3AA72425A62DAE755C3D1FB126649D0F7` | `0C491663B1310F5804A462FC48E91B4E8CF6CBED` | `EEDD323D67CA8D3B1CF45BD50052DA3C` |

## Metadata

- **Filename:** `netcxrd_1.sys` (Identical copies: `netcxrd_2.sys`)
- **Size:** 331776 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** unsigned
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** —
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

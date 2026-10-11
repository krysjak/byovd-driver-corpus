# `wintun.sys`

[Back to index](../README.md) · [Українська версія](wintun.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A7BB3555C5419BEFB1A5F54267DCAE9A7AF16749DDF4EEF9B431FCF0B863110` | `1E0DD7B0D0C0B880BF6864134D1E792E80E875FC` | `43D91124FE8112D0027842824DAD7326` |

## Metadata

- **Filename:** `wintun.sys` (Identical copies: `wintun_1.sys`)
- **Size:** 29592 bytes
- **Architecture:** 0x8664
- **Company:** WireGuard LLC
- **Product:** Wintun Driver
- **Description:** Wintun Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

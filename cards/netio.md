# `netio.sys`

[Back to index](../README.md) · [Українська версія](netio.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `801CB171DAC254C3C280B8F06C6C0F08236C42F771364E55680B536C964C5B3D` | `2F2364E559E8BBE96598AA4A752E0DF2A55ACADC` | `71AA515E1591C267866BEE4F53F70088` |

## Metadata

- **Filename:** `netio.sys`
- **Size:** 746992 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Network I/O Subsystem
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `driver loading`

**Imports:** `IoAllocateMdl`, `ZwLoadDriver`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

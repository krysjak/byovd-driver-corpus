# `vmswitch.sys`

[Back to index](../README.md) · [Українська версія](vmswitch.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EBDADFDD063845195F08619FE987105D119A29572BACBE441BE374BE0F021FD1` | `6717A93F968BF613A9D505AD6A284CFADE1364B1` | `341C34EA6F70C8F9263A4ACA38E1236E` |

## Metadata

- **Filename:** `vmswitch.sys`
- **Size:** 2569680 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Microsoft® Network Virtualization Service Provider
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

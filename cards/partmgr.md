# `partmgr.sys`

[Back to index](../README.md) · [Українська версія](partmgr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `978267BFE7B8967F4A560BF6178FBED7D5953040CDE4EC7A4E69A8C14D2071EC` | `7502D81D07D1289EA71D211ABCCD6B43AEC95CE1` | `5797DD3B622B0A6E113A90F993A522E2` |

## Metadata

- **Filename:** `partmgr.sys`
- **Size:** 226800 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Partition driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

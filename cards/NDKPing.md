# `NDKPing.sys`

[Back to index](../README.md) · [Українська версія](NDKPing.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B515174A7FC47B0E48DA6E7AB1190978E9FA55FDC9AE2E4A3C0D0B42082DE117` | `0B3E2C19F1C851E43285C0361D8E4A2AD7D8EF52` | `B64B91C41B77FCD873C38F8BDCD2C4A7` |

## Metadata

- **Filename:** `NDKPing.sys`
- **Size:** 112112 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** RDMA Sample Driver
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

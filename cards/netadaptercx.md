# `netadaptercx.sys`

[Back to index](../README.md) · [Українська версія](netadaptercx.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `35E8D4B8BE124840410A69AF486C30600A623E105B6127876518E53B9E8EC19E` | `A673F3D365AF6DAE5B299AC690593B7164BFEEA7` | `B22FD227938A4C383E667FC5B6D9E0EF` |

## Metadata

- **Filename:** `netadaptercx.sys`
- **Size:** 394752 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Network Adapter Class Extension for WDF
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `process address-space attach`

**Imports:** `KeStackAttachProcess`, `MmGetPhysicalAddress`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

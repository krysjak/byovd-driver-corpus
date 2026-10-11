# `devmap.sys`

[Back to index](../README.md) · [Українська версія](devmap.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6062003A59F3B7CE48C8D2899DCDC51847816A5831E15555B6A92C154E55CD2B` | `62F94E42F5BC4BC9BBCE350C2CF5737D3B0CCC5F` | `EAE51D912CBCB6FC328848A2AB9F7951` |

## Metadata

- **Filename:** `devmap.sys`
- **Size:** 57344 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Device Mapper Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

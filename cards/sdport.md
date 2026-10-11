# `sdport.sys`

[Back to index](../README.md) · [Українська версія](sdport.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B8E738D974FC5D618665CE8CA2B1BB3C0A1BED09855B8B9BE39754EBD9AD6FED` | `53D8576B5AAAA6BD8E89E08DB3F98A0AC656B2D0` | `4ACC1409B80C14911F44D7AA9EE94DE9` |

## Metadata

- **Filename:** `sdport.sys`
- **Size:** 140600 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** SD Host Controller Port Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

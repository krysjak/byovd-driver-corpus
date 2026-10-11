# `hdaudbus_2.sys`

[Back to index](../README.md) · [Українська версія](hdaudbus_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C0BC942BD672FF3F8C6EDD8AFB4AE140AF3EF411CE4C6033B4A8FC3A584E73E3` | `F869E48A7EC0B2EA5CA9D411BDF14100284366F0` | `916AA4C5B4C1AB61040AA0C0E11B83E2` |

## Metadata

- **Filename:** `hdaudbus_2.sys`
- **Size:** 204800 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** High Definition Audio Bus Driver
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

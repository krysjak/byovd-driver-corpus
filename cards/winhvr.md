# `winhvr.sys`

[Back to index](../README.md) · [Українська версія](winhvr.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D407FC49711176E3E8F3E4ECF68121AB7031804C9058B3D893ACC92DEECA1CE` | `A5C71E8B8CE66F1220C3C4EF6B28C85B8A8F3B91` | `D53BE6E7188953AE164C4E69EC0163A9` |

## Metadata

- **Filename:** `winhvr.sys`
- **Size:** 153064 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Windows Hypervisor Root Interface Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

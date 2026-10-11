# `ipt.sys`

[Back to index](../README.md) · [Українська версія](ipt.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E14223E74D1BDA76DAE04ECEBA0EAA865C624581FBDDCA31395DF902A7837ED8` | `BA5711B674A456DB57A5681B81DAC2EE25DA4B6F` | `491C1C826221375281CC169922981B12` |

## Metadata

- **Filename:** `ipt.sys`
- **Size:** 103936 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** IPT Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

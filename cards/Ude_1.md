# `Ude_1.sys`

[Back to index](../README.md) · [Українська версія](Ude_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `45A5B65F5605F9B264504AE958897AB9C47F88D4A7CAF392A031FDA141470D04` | `E0D137893284814DDEB418AD3F304469AB2F59C6` | `1047DDE8EFDC2D1C77AD55A0C11F4EEE` |

## Metadata

- **Filename:** `Ude_1.sys`
- **Size:** 351672 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Telephony Stack
- **Description:** UDE Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

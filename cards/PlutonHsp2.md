# `PlutonHsp2.sys`

[Back to index](../README.md) · [Українська версія](PlutonHsp2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FF60A7A86D4593AB3E29E90270AF28BD48C80A1C7FBC0CEEFEF57718CDB782E0` | `F8BCA9C5DF014F482AC939FC5956A7E93C622F30` | `22F1E904A01216F9C595E91DB60CB06C` |

## Metadata

- **Filename:** `PlutonHsp2.sys`
- **Size:** 75248 bytes
- **Architecture:** 0x8664
- **Company:** —
- **Product:** —
- **Description:** —
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

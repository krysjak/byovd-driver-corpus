# `cng.sys`

[Back to index](../README.md) · [Українська версія](cng.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C6BEE721C0FB2BCBE02F92308828CBF8E9CEFC1EC131198B0F86627CA54D41F` | `5552E1AEF89EC1C66B886DA67FF48A8E970E272A` | `605A5A569CEF7F43A0996A1A484904AC` |

## Metadata

- **Filename:** `cng.sys`
- **Size:** 964288 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Kernel Cryptography, Next Generation
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `driver loading`, `process lookup`, `system information set`

**Imports:** `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

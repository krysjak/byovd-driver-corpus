# `fse.sys`

[Back to index](../README.md) · [Українська версія](fse.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3E1898007BED6FE0D8932D21A013E7826EB04F17A89F3270B66BE4351E940031` | `91EDDA5F5369E525850F6D3FFCE09BC848B067DA` | `11D99CF92024A07AC41E43F57B316D64` |

## Metadata

- **Filename:** `fse.sys`
- **Size:** 230888 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Flow Steering Engine Driver
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

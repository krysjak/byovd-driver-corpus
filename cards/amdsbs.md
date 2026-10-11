# `amdsbs.sys`

[Back to index](../README.md) · [Українська версія](amdsbs.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AFA0A9EACCC36CFC88AC41DCD0149AC6F9763D12C898397E831D80F202EF4402` | `3D2ED79A4B29BF3D29C6BA549F8B1BD56400764C` | `C516B52D95F7581C2F6D15D83771C472` |

## Metadata

- **Filename:** `amdsbs.sys` (Identical copies: `amdsbs_1.sys`)
- **Size:** 260512 bytes
- **Architecture:** 0x8664
- **Company:** AMD Technologies Inc.
- **Product:** AMD Technology AHCI Compatible Controller
- **Description:** AMD Technology AHCI Compatible Controller Driver for Windows - AMD64 platform
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

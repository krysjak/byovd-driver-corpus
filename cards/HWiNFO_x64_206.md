# `HWiNFO_x64_206.sys`

[Back to index](../README.md) · [Українська версія](HWiNFO_x64_206.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D4250BC1528F92C262DD425B490874BDBEF224761E130716766924B95F3C8B2` | `D5C05FDD5BEC31A2FDCBB56C4AF0167F1549F318` | `736C636F1D686CF9B08299A56FCFDE79` |

## Metadata

- **Filename:** `HWiNFO_x64_206.sys`
- **Size:** 57512 bytes
- **Architecture:** 0x8664
- **Company:** REALiX
- **Product:** HWiNFO AMD64 Kernel Driver
- **Description:** HWiNFO AMD64 Kernel Driver
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

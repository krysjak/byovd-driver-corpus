# `TeeDriverW8_2.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EAD78FEE4054C4508ECFE4A2AFD73BF3B2FB212F215E9128BAC3B72A2BED436F` | `BAA3A157B6B768753C8BAF6D9B13CC1565A6DB64` | `E5AA14C43888A103A8ACE362D45FDC44` |

## Metadata

- **Filename:** `TeeDriverW8_2.sys`
- **Size:** 177664 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

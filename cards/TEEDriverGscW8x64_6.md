# `TEEDriverGscW8x64_6.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C9F812139E234468E68B77DA6C80569D6E782D8C42555792A545449359BB440` | `437FE7195B8BB486D51D637EB59833E0ED476A24` | `AD6F6638FFAC51780A176AD30C7D4B1F` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_6.sys`
- **Size:** 280672 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

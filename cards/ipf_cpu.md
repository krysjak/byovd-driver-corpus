# `ipf_cpu.sys`

[Back to index](../README.md) · [Українська версія](ipf_cpu.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D104C6F2E9EFCC92B4D01BB3E826505618CA868E60E54195D8A48450CC6DE540` | `5F167FB144E980ECA15A6D00CAD27D924FBC51BC` | `F3F28DD1CD24D4A29DA3058D46A498D4` |

## Metadata

- **Filename:** `ipf_cpu.sys`
- **Size:** 89672 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Innovation Platform Framework
- **Description:** Intel(R) Innovation Platform Framework CPU Participant
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

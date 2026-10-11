# `dptf_cpu_7.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36628984FB45C711AF6D230D4B8B565AF7E94BC3F5E5C0C3BE4D867AEC01B97D` | `415334B5F4F7FAFDB9C657740941C4971E4E72F3` | `2E034D188092D6DCAE2CC35BA326F684` |

## Metadata

- **Filename:** `dptf_cpu_7.sys`
- **Size:** 74120 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Dynamic Tuning
- **Description:** Intel(R) Dynamic Tuning CPU Participant
- **Signature:** signed
- **Source:** `oem:hp`
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

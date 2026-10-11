# `dptf_cpu_3.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB97B9AE8AB841247F13A9CEC6CE6362B029FBF1960BAA2E50CC4E3A0A4398AF` | `73934EE08D24EC591E019843459D7BD394C74A94` | `734BF685B5E1843AE447165E25B42B70` |

## Metadata

- **Filename:** `dptf_cpu_3.sys`
- **Size:** 73368 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Dynamic Tuning
- **Description:** Intel(R) Dynamic Tuning CPU Participant
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

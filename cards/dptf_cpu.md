# `dptf_cpu.sys`

[Back to index](../README.md) · [Українська версія](dptf_cpu.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `055E96F20FFFBCD1EDE806F3F816FDAA6FE91D16F792542CF76C8D727BFC394C` | `735788FB8431B85EC4E61BD6840B2D7980C77D9F` | `4EADF6F3F9CF90CCF0E3AC2E44E61B76` |

## Metadata

- **Filename:** `dptf_cpu.sys`
- **Size:** 76936 bytes
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

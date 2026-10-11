# `ipf_cpu_1.sys`

[Back to index](../README.md) · [Українська версія](ipf_cpu_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `94C8F59C816A477E6A3F17E02863DBBBAF0241B2A96010CBF7FA406DB2785686` | `ABEF78F622360C0B3C5D933A5A2893568CC957EE` | `26EDB48D962EB1DCE5E92E1E0C83B69C` |

## Metadata

- **Filename:** `ipf_cpu_1.sys`
- **Size:** 79512 bytes
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

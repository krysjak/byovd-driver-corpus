# `TEEDriverW10_2.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6D9D0EBA3339CB58AFF4B5F255FAB8556DEBB4C8FCDC524C7F50F6A0404B3279` | `4B033674A3E990417B95205CF394D50AA0ED7E49` | `F8FE2E67168859EF1AC9363231A6581F` |

## Metadata

- **Filename:** `TEEDriverW10_2.sys`
- **Size:** 264736 bytes
- **Architecture:** 0x14c
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

# `TEEDriverW8_7.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8273F2510EF4EA39AECBDA29ABA0FAB14B3D42FAFBB8811B789AFF0242BD6C59` | `7933CAF2132B4BD4C2395F830785010805B3ED92` | `A30C0B52EB63229C61ABA6CFC6B0966B` |

## Metadata

- **Filename:** `TEEDriverW8_7.sys`
- **Size:** 244336 bytes
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

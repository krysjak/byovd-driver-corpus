# `TEEDriver_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriver_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E4B1397A941828CEE7D90D0E7C36360BBA26AE5859A4EE2A1E246F52C3957B63` | `8EEA06323F7A897E1A7976F04FD95B0118C0CA1B` | `87CD837BC89F1ADAEC3EA00B9227B39C` |

## Metadata

- **Filename:** `TEEDriver_1.sys`
- **Size:** 155424 bytes
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

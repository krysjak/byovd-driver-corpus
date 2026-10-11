# `HECI_1.sys`

[Back to index](../README.md) · [Українська версія](HECI_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0419A59DB73A908C2ED987BEFDBDDEBA3E96C74AB55A29D5D91AFBF9A2B0AF6B` | `233095064A32D9410D6194C72C29828D181E9C14` | `6FAB8EE0457E9795D93B91405766E674` |

## Metadata

- **Filename:** `HECI_1.sys`
- **Size:** 56320 bytes
- **Architecture:** 0x14c
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 80

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

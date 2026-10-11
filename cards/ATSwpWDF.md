# `ATSwpWDF.sys`

[Back to index](../README.md) · [Українська версія](ATSwpWDF.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `250FE2B40D9FC73574358858D3922DFD6EE3219E2A8008D786D1D23015E681AC` | `8AEBD5AF8A32EE8280253B13604CD2BEE1C10E5E` | `D8ED748B592CE1374D1DA69CE44E2719` |

## Metadata

- **Filename:** `ATSwpWDF.sys`
- **Size:** 542880 bytes
- **Architecture:** 0x14c
- **Company:** AuthenTec, Inc.
- **Product:**  Swipe Fingerprint Sensor WDF USB Driver
- **Description:**  AuthenTec Swipe Sensor WDF USB Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`

**Imports:** `MmMapIoSpace`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

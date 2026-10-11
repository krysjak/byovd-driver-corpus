# `MhiHost.sys`

[Back to index](../README.md) · [Українська версія](MhiHost.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5054E023AD7C3013CA80DCD0A469183825B2E6951AB81BEF5A3B5232DB2F0055` | `4F284F7C9A637CAF5A8E50DC8596239C375CE3C6` | `56643D8DAE3E981A4A49173816837090` |

## Metadata

- **Filename:** `MhiHost.sys`
- **Size:** 175952 bytes
- **Architecture:** 0x8664
- **Company:** Qualcomm Technologies, Inc.
- **Product:** Qualcomm Modem Host Interface Driver
- **Description:** QUALCOMM Modem Host Interface Driver
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

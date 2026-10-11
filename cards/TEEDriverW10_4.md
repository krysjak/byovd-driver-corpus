# `TEEDriverW10_4.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `95935FFC847E48FA26A325BE1F9C52097E34B3E12D5BAA299D804B4BBC1F7E8E` | `6AB85EA2897678762B296B4757000A416D5528DD` | `84977E3A703A4042EC0FAB9A410DB728` |

## Metadata

- **Filename:** `TEEDriverW10_4.sys`
- **Size:** 267976 bytes
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

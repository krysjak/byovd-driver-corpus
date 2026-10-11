# `TEEDriverW10.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F1D4E2C4AEBA9401AB87C77F2BBFD0D0F1E4667D6C6653A41F7C79822494CEAE` | `0E9066366B4CBFDE940B68B36D889934B3C74F9B` | `145C0A79671AD6ADFC18A0B65089C506` |

## Metadata

- **Filename:** `TEEDriverW10.sys`
- **Size:** 271328 bytes
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

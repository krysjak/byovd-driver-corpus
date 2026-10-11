# `TEEDriverW10_5.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_5.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `34026BB2D115F5F9867A05E6309FCD19D4B58480E71740C8989EB65AA406E3B0` | `DA7635D84E3A1ED1E114327DEE7EDE6E09698FF1` | `8BF4413DC76A755E18253FAECC6D1F16` |

## Metadata

- **Filename:** `TEEDriverW10_5.sys`
- **Size:** 263824 bytes
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

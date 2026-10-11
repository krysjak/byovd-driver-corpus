# `TEEDriverW10x64.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37BDFD478D64A53975452970AF44A88053206EFB2CF30D505E60E62BB383FD96` | `86C9685955FF6CC150E62C640EE83A695B6EC455` | `9DAAE14E013F21B67A51F5A275B6FBFC` |

## Metadata

- **Filename:** `TEEDriverW10x64.sys`
- **Size:** 326144 bytes
- **Architecture:** 0x8664
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

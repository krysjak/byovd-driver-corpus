# `TEEDriverW10x64_3.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `00734AFFECA068311AA21270E58E4453FA1069E06C4A8FC5D2F6CF1576253511` | `A3B379177F91D4685A94FCD9468B669A711FC785` | `839E946563E78470EE460F962E047442` |

## Metadata

- **Filename:** `TEEDriverW10x64_3.sys`
- **Size:** 321128 bytes
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

# `TEEDriverW10x64_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4284462F0FDCBDDD13C2A86FD7508D5D16B57522C476CF7CFDD7141320FC7B5D` | `49D6143B2763220F817F84968CD1BE0EDAF2EFC3` | `0B84B5DE351B6E990A2F71FB7DA4536D` |

## Metadata

- **Filename:** `TEEDriverW10x64_1.sys`
- **Size:** 327648 bytes
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

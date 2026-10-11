# `TEEDriverW10x64_4.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A2E0B9EA4973BC875BAF685C684ED007407D05AB0BB053C3FB72D6357106A571` | `EDDC4FCB2CE978FD502A66F27226CD4910747A82` | `EAF180CED3A07245F238ED21D9C68975` |

## Metadata

- **Filename:** `TEEDriverW10x64_4.sys`
- **Size:** 323264 bytes
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

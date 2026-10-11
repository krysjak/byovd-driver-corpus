# `TEEDriverx64_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverx64_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4158BE66A9DED8555FD62844EDE908B7B5C64DEDA55B32BFC8BDE3534B0ABA91` | `8E5667C32DE29B689B194FC810BF82438BA2C0BE` | `124B5296DF58E1F0ED3E9122431B136D` |

## Metadata

- **Filename:** `TEEDriverx64_1.sys`
- **Size:** 178976 bytes
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

# `TeeDriverW8x64_3.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8x64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5D8AF9775DF9A1C3BA0AF87A042621B0587CA2F36BFCACEDF10F4CDCB0F0A2AB` | `CFE40C6CC011A21E40282F121AA573BBE45587F4` | `0AC256421B38CEF110FD2C6A22421E65` |

## Metadata

- **Filename:** `TeeDriverW8x64_3.sys`
- **Size:** 205984 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 70

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

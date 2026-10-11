# `TeeDriverW8x64_6.sys`

[Back to index](../README.md) · [Українська версія](TeeDriverW8x64_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `903B37C0954BF84EFD9FA11195FADF9C50EED83DC2F521C8659052500061F011` | `9D0FA9188D007C50FE9C155BC88C480EE9813A62` | `12AE4DD10B08A72FD814D502377EC709` |

## Metadata

- **Filename:** `TeeDriverW8x64_6.sys`
- **Size:** 228808 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Management Engine Interface
- **Description:** Intel(R) Management Engine Interface
- **Signature:** signed
- **Source:** `oem:hp`
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

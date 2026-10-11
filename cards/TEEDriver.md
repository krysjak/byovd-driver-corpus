# `TEEDriver.sys`

[Back to index](../README.md) · [Українська версія](TEEDriver.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BC7DCC7722A4A1AC9F8D705F8819C9D227696A9538BBF6A52EB7C27969FD3A21` | `F9D9801659D05CE175AA30D18BC00DB160752BEC` | `113412F2962F700710BB22FCFE266B65` |

## Metadata

- **Filename:** `TEEDriver.sys`
- **Size:** 85464 bytes
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

# `TEEDriverW10_6.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `19BE751C49DFE9CE923085B4F4D9D1555B754C4C735272E76D3EE8D535703AE2` | `84FBE3F46B2E3A880679E3A09D0E8B5E6C750A67` | `330AFA77575F60BD628D78DFC5F6B22F` |

## Metadata

- **Filename:** `TEEDriverW10_6.sys`
- **Size:** 254856 bytes
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

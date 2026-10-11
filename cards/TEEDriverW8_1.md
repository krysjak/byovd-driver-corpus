# `TEEDriverW8_1.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW8_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EE970B70136F47ED5F4FC32EC83FF1DD2E11F2228FC91F077151FE7AF927A7BC` | `5A3C763DF11AB784F5474A8D3D9AC7A5B02439E4` | `75A24FF735BCA61F38C24F88D1E4D34C` |

## Metadata

- **Filename:** `TEEDriverW8_1.sys`
- **Size:** 162080 bytes
- **Architecture:** 0x14c
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

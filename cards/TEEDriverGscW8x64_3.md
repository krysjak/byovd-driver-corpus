# `TEEDriverGscW8x64_3.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverGscW8x64_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8F31DE9401E98A32E834457444342C49F0DDD5EEE9436D3655E9671E4F89071C` | `310C7D6927A086673DA19C1782A805EBBCD0E37E` | `ECC0CAEDEF7DCF123AEC2FBB9FA7AA54` |

## Metadata

- **Filename:** `TEEDriverGscW8x64_3.sys`
- **Size:** 276416 bytes
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

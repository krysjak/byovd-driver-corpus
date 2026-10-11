# `atihdwt6_3.sys`

[Back to index](../README.md) · [Українська версія](atihdwt6_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F6CFB657EF0488959A637459DF2278419ABA3DEDDEF731156DCBD5DBB3C5817E` | `0BA77854DD164577E30191D7E75C513F4AB34513` | `08D3A5CE2FE501438099002524E26E5F` |

## Metadata

- **Filename:** `atihdwt6_3.sys`
- **Size:** 107936 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
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

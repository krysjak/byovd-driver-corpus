# `AtihdWT6_1.sys`

[Back to index](../README.md) · [Українська версія](AtihdWT6_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C2CC65D95969206710A0B671EF50C74FF5CEA89873778362ECC76975490B2ED` | `9E69E51E9647E4AE6455C92954C8F3E8CC8CC19B` | `E4E2AAD101A16EE511B73F251A1686E5` |

## Metadata

- **Filename:** `AtihdWT6_1.sys` (Identical copies: `AtihdWT6_2.sys`)
- **Size:** 259992 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices
- **Product:** AMD HD Audio Driver
- **Description:** AMD High Definition Audio Function Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 60

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

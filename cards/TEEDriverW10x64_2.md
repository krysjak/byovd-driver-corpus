# `TEEDriverW10x64_2.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10x64_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `947F553D885EEDB7621E9E3ED63DF24387F312CF3113EFAC74A81400F7182D5B` | `739241A537B45B810AC932566DAEFC4CD5CCE800` | `DB79C4B46EC10643EFAB119B95B4F3F2` |

## Metadata

- **Filename:** `TEEDriverW10x64_2.sys`
- **Size:** 317984 bytes
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

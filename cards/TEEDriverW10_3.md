# `TEEDriverW10_3.sys`

[Back to index](../README.md) · [Українська версія](TEEDriverW10_3.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C14B796732E4ED65903A0FDE82B1D341435C32EC3B7CDCF5D8DE7E1523F66F6E` | `B7197020AA93742B4A4252F04C888972291B5EB0` | `277B9BE65B769565D2C88BF446539F1E` |

## Metadata

- **Filename:** `TEEDriverW10_3.sys`
- **Size:** 266336 bytes
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

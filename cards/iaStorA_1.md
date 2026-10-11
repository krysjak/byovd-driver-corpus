# `iaStorA_1.sys`

[Back to index](../README.md) · [Українська версія](iaStorA_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0C6B684781D27F423D20186A40D7513DD6ABC38AD286D013791B37CBF5477A55` | `2E35581C262F81BA931EA0DB1962CCE268949FCC` | `71341219FBB4BAB7F2462C4267DAB594` |

## Metadata

- **Filename:** `iaStorA_1.sys`
- **Size:** 644968 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel Rapid Storage Technology driver 
- **Description:** Intel Rapid Storage Technology driver - x64
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

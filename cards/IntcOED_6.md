# `IntcOED_6.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_6.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `898E935522E3BCA28741D8391A17783721AA63C20162FD97C9B2CA123AA8185A` | `272A6B99205319D5A27D4F6B9AFE54CD9E843C0D` | `26BC16E6C7AEC2104E8005543DCB3F4F` |

## Metadata

- **Filename:** `IntcOED_6.sys`
- **Size:** 1168456 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel® Smart Sound Technology (Intel® SST) OED
- **Description:** Intel® Smart Sound Technology (Intel® SST) OED
- **Signature:** signed
- **Source:** `oem:dell`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 75

## Capability profile

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

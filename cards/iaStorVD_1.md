# `iaStorVD_1.sys`

[Back to index](../README.md) · [Українська версія](iaStorVD_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D2F5E62F6717E9DF8925E29B4B8789316505CB2D8B6EA0D22104249F692B7C8` | `EA6F13E7031BBCC5317519F288FDA8DBFF255BA5` | `514A0D2FCA07453604D8DD26B34A5961` |

## Metadata

- **Filename:** `iaStorVD_1.sys`
- **Size:** 1623632 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Rapid Storage Technology driver 
- **Description:** Intel(R) Rapid Storage Technology driver - x64
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

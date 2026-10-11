# `IntcOED_11.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_11.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `80E310FE4ACCF88FB9EABE3DAE1E659BBEBA415302B354C491B104EC9E10BA5D` | `4DCC905A16A2634290B5295BAB07BE316539E7B4` | `63D433D6C561FCC54EEBC210B667BE72` |

## Metadata

- **Filename:** `IntcOED_11.sys`
- **Size:** 742488 bytes
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

# `IntcOED_4.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_4.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `68509AFB148C081C6695F986C0AA5C82250D8EA242361E5BD8F1412CBA9247BC` | `636AEE3ED89FA260D4F0BB93E35D334B850B1FA7` | `AE800B8AFF888187BF6812DC52DA2E8F` |

## Metadata

- **Filename:** `IntcOED_4.sys`
- **Size:** 1293240 bytes
- **Architecture:** 0x8664
- **Company:** Intel(R) Corporation
- **Product:** Intel(R) Smart Sound Technology OED
- **Description:** Intel(R) Smart Sound Technology OED
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

# `IntcOED_7.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_7.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACABB510C4DE938B0D58970F3CCEC8B221100B31766480C29892253C5E7F5A1F` | `15C1F13176101DD8CEA21F90207D6F1C09CF8D6A` | `C7D6DDA8589923515D56B46DF83DFD1D` |

## Metadata

- **Filename:** `IntcOED_7.sys`
- **Size:** 1289168 bytes
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

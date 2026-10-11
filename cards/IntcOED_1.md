# `IntcOED_1.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A7D0D4E16E586966A9E2898DA3DFB7AA38700A10D31C036326D46FFED127B3BB` | `CB1543D86FFD37CBAB76477AB2980450B73EC2CF` | `B93BCEA86B99E9A356DB6B0B26E7B239` |

## Metadata

- **Filename:** `IntcOED_1.sys`
- **Size:** 1283672 bytes
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

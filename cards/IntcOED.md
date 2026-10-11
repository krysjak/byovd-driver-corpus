# `IntcOED.sys`

[Back to index](../README.md) · [Українська версія](IntcOED.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A6C48B72EEC7CC13853591093077A1CED4250547D07009F32AD441DEAF6DBDD1` | `37E96401278146D8A296EDB19039D74D7D46BBB3` | `6486FBD9937060A41E2DDE200EA56CA1` |

## Metadata

- **Filename:** `IntcOED.sys`
- **Size:** 1317840 bytes
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

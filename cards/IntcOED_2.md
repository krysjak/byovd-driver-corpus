# `IntcOED_2.sys`

[Back to index](../README.md) · [Українська версія](IntcOED_2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `82489010B984E79046BC4716DD23AC35D375AE27EA179175B00846411523A517` | `1DCD9BDD974C2B6DF2BBAF3A63AFA51D4A58FBD7` | `F4D6453A5C75535E06E40B866F20E2EA` |

## Metadata

- **Filename:** `IntcOED_2.sys`
- **Size:** 835776 bytes
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

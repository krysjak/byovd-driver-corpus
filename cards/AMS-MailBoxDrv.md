# `AMS-MailBoxDrv.sys`

[Back to index](../README.md) · [Українська версія](AMS-MailBoxDrv.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C8D3EA847F70AC079D8911C72258E911F3F26D241700B52C0E47991F23388091` | `6EE6A9FAF038654776ED6F6EEF0633F7AD1E6797` | `7965363605BCB2BF08C681499A932FB7` |

## Metadata

- **Filename:** `AMS-MailBoxDrv.sys`
- **Size:** 125168 bytes
- **Architecture:** 0x8664
- **Company:** Advanced Micro Devices, Inc
- **Product:** AMS-MailBoxDrv
- **Description:** AMS-MailBoxDrv
- **Signature:** signed
- **Source:** `oem:hp`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** OEM package
- **Score:** 85

## Capability profile

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

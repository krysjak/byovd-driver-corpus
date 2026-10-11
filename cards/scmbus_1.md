# `scmbus_1.sys`

[Back to index](../README.md) · [Українська версія](scmbus_1.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B74B50A7B6FF78338E48BBC4D631DC095F3EDE6A1FD7B9AFEE26E78824AE5511` | `EF1ADD5CB0C74AE7ACE6A83DD5AECE3576F6727B` | `99E5816422FE467759A2DC6A8FD300AA` |

## Metadata

- **Filename:** `scmbus_1.sys` (Identical copies: `scmbus_3.sys`)
- **Size:** 263576 bytes
- **Architecture:** 0x8664
- **Company:** Microsoft Corporation
- **Product:** Microsoft® Windows® Operating System
- **Description:** Storage Class Memory Bus Driver
- **Signature:** signed
- **Source:** `local`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** yes
- **On systems:** Live system
- **Score:** 90

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

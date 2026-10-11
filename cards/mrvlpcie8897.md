# `mrvlpcie8897.sys`

[Back to index](../README.md) · [Українська версія](mrvlpcie8897.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `72EE4E962868C1C345A8D4E93ADE0CCD919C369471DE4D049BEF59BD3642407B` | `CF9842B5EA9951FA08438D6764A4873B3554424A` | `5ADE5BC51D4330F39C1AB27C5D17A46C` |

## Metadata

- **Filename:** `mrvlpcie8897.sys`
- **Size:** 1036288 bytes
- **Architecture:** 0x8664
- **Company:** Marvell Semiconductors Inc.
- **Product:** Marvell LE Driver
- **Description:** Marvell LE Driver for the WiFiCLass Stack
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

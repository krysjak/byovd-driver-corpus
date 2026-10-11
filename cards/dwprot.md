# `dwprot.sys`

[Back to index](../README.md) · [Українська версія](dwprot.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F80AB81552926676E833D8A925303F6602988016241F54B6E496C049407CFE06` | `89F2D99F158A188BCD45964F893C23033EFF5AAC` | `5ACE1DEEF102DF84FC7FAF497D132C98` |

## Metadata

- **Filename:** `dwprot.sys`
- **Size:** 153880 bytes
- **Architecture:** 0x8664
- **Company:** Doctor Web, Ltd.
- **Product:** Dr.Web Anti-Virus
- **Description:** Dr.Web Protection for Windows
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** yes · **Creates symlink:** yes · **Missing probe validation:** —
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `process address-space attach`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `KeStackAttachProcess`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

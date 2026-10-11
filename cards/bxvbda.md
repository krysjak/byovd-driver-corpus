# `bxvbda.sys`

[Back to index](../README.md) · [Українська версія](bxvbda.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FCA12E3ABA77F5A64A54431969EDC8B32E1A8F3F6FC06282120FE003B2BE1B9` | `0CC5AA83F863A0A877B44B7F1D7AC79A284C4586` | `56B18293198BA954762BC0688AB82571` |

## Metadata

- **Filename:** `bxvbda.sys` (Identical copies: `bxvbda_1.sys`)
- **Size:** 534944 bytes
- **Architecture:** 0x8664
- **Company:** QLogic Corporation
- **Product:** QLogic Gigabit Ethernet
- **Description:** QLogic Gigabit Ethernet VBD
- **Signature:** signed
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

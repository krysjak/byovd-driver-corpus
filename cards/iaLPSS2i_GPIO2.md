# `iaLPSS2i_GPIO2.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_GPIO2.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6FF5D13EF69E8FBCB4772C7B5C4D5770C78E0B29F9164FA1611EFDE91CE876BE` | `BFB14D74BF8088F99E96C6BBD036C320F913E7F7` | `6C3EDE394C71D5A67A504F55E35B6F47` |

## Metadata

- **Filename:** `iaLPSS2i_GPIO2.sys` (Identical copies: `iaLPSS2i_GPIO2_1.sys`)
- **Size:** 79360 bytes
- **Architecture:** 0x8664
- **Company:** Intel Corporation
- **Product:** Intel(R) Serial IO Driver
- **Description:** Intel(R) Serial IO GPIO Driver v2
- **Signature:** unsigned
- **Source:** `candidate_drivers`
- **Added to repo:** 2026-10-11
- **Creates device:** — · **Creates symlink:** — · **Missing probe validation:** yes
- **On systems:** Unknown
- **Score:** 0

## Capability profile

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Documented usage (LOLDrivers)

No public usage documentation. Candidate by static heuristic — dangerous imports present, vulnerability NOT confirmed.

## Detection

Block/detect by SHA256, SHA1 or filename. Monitor driver-load events (Sysmon 6, Defender for Endpoint) for these hashes.

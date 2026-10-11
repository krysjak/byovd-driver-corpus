# `iaLPSS2i_GPIO2_CNL.sys`

[Back to index](../README.md) · [Українська версія](iaLPSS2i_GPIO2_CNL.uk.md)

## Hashes

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E353D90D0B79A70F976FD5EA1CB7E25A97835E25116962EA035424715B2F43FE` | `B069D53CE6CE3A5EF35F985285D2BF7F6114C8CA` | `87DDDAE1693484BD0A210C877BDA00C2` |

## Metadata

- **Filename:** `iaLPSS2i_GPIO2_CNL.sys` (Identical copies: `iaLPSS2i_GPIO2_CNL_1.sys`)
- **Size:** 112128 bytes
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
